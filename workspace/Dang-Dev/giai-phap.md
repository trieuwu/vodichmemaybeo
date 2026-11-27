# Giải pháp MVP: "Đủ Ngay Lần Đầu"

> Hack4Biz Round 1, Bank X. Vấn đề đã chọn: hồ sơ vay SME bị thiếu hoặc sai khi nộp.
> Số liệu lấy từ `case_study.md`. Mục nào là giả định đều ghi **[Giả định]**.

## 1. Ý tưởng chốt

Biến bước chuẩn bị và nộp hồ sơ thành một **danh sách việc cần làm riêng cho từng khách**:

1. Khách biết chính xác mình phải nộp giấy tờ gì.
2. Mỗi giấy tờ được nộp vào đúng ô của nó và được chụp đủ rõ.
3. Hệ thống không cho nộp khi còn thiếu mà không có lý do.
4. Nếu nhân viên vẫn phát hiện lỗi, khách nhận **đúng một yêu cầu bổ sung**, có link mở thẳng tới chỗ cần sửa.

MVP **không cần AI mới hay dịch vụ bên thứ ba**. Nó chỉ mở rộng các hệ thống ngân hàng đang có, nên tránh được rủi ro chờ phê duyệt (Section 6).

## 2. Vấn đề

**Người bị ảnh hưởng**
- **Chủ SME, nhất là người nộp lần đầu:** phải nộp lại và chờ lâu hơn.
- **Nhân viên Credit Operations và RM/CSKH:** mất thời gian liên hệ khách và kiểm lại hồ sơ.

**Định nghĩa vấn đề:** Khách SME thường nộp hồ sơ thiếu, khó đọc hoặc xếp sai loại. Lý do là danh sách giấy tờ thay đổi theo sản phẩm vay và hồ sơ khách, trong khi portal chỉ kiểm tra định dạng và dung lượng file. Nhân viên vì vậy phải yêu cầu bổ sung sau khi khách đã nộp, làm hồ sơ chậm lại và tốn công cả hai bên.

**Bằng chứng**

| Số liệu | Nguồn |
|---|---|
| 780/1.200 hồ sơ mỗi tháng (**65%**) phải bổ sung, tốn khoảng **130 giờ nhân viên** (780 × 10 phút) | Exhibit A |
| Thời gian trung vị đến khi xong review ban đầu: **8 ngày** nếu phải bổ sung, **4 ngày** nếu không | Exhibit A |
| Người nộp lần đầu: **75%** phải bổ sung (600 hồ sơ, chiếm 77% tổng số ca bổ sung) | Exhibit B |
| 32% hồ sơ phải bổ sung (khoảng 250) không sửa xong trong 1 ngày làm việc | Exhibit A |
| **78%** hồ sơ bắt đầu trên điện thoại; **41%** tài liệu là ảnh chụp hoặc scan | Exhibit A, D |
| Portal không kiểm tra đầy đủ việc hồ sơ đã đủ giấy tờ hay chưa | Section 5 |

> Lưu ý: chênh lệch 8 và 4 ngày không hoàn toàn do việc bổ sung (Exhibit A nói có thể có yếu tố khác). Bài chỉ nên nói việc bổ sung **góp phần** làm chậm hồ sơ.

**Vì sao chọn vấn đề này trước:** đây là vấn đề tốn nhiều giờ nhân viên nhất (khoảng 130 giờ, so với khoảng 33 giờ cho câu hỏi về trạng thái). Nó cũng giải được mà không cần AI, khác với nhập liệu tay (khoảng 84 giờ) vốn cần OCR/AI chưa được duyệt.

## 3. Product Goal

> **SME nộp được hồ sơ vay đầy đủ, đúng loại và đọc được ngay từ lần đầu, kể cả trên điện thoại, để ít phải bổ sung hơn và hồ sơ đến bước review ban đầu nhanh hơn.**

**Giả định quan trọng cần kiểm chứng:** phần lớn ca bổ sung thuộc các lỗi mà checklist và bước kiểm tra trước khi nộp có thể ngăn được, gồm:
- không biết cần giấy tờ nào,
- nộp sai loại,
- ảnh khó đọc.

Giả định sẽ sai nếu nguyên nhân chính là khách *chưa có* giấy tờ.

**Cách kiểm chứng trong Sprint 1:**
- BA cùng Credit Operations phân loại lý do bổ sung trên mẫu khoảng 50 ca gần nhất, dùng quỹ giờ tư vấn 2 giờ/tuần.
- Nếu phần lớn lý do nằm ngoài khả năng ngăn chặn, PO sắp xếp lại backlog.

## 4. Bốn thành phần của MVP

### 4.1 Checklist giấy tờ riêng cho từng khách
- **Làm gì:** trước khi upload, khách trả lời 4–5 câu hỏi (loại khoản vay, loại hình doanh nghiệp, số năm hoạt động, có tài sản đảm bảo hay không). Portal hiện đúng danh sách giấy tờ khách đó cần. Mỗi mục có ảnh mẫu và giải thích dễ hiểu, ví dụ "lấy ở đâu", "cần trang nào".
- **Giá trị:** khách không phải đoán. Người nộp lần đầu hưởng lợi nhiều nhất.
- **Dùng lại hệ thống:** bộ quy định giấy tờ nội bộ, portal hiện có.

### 4.2 Ô upload theo giấy tờ và chặn nộp mềm
- **Làm gì:**
  - Mỗi giấy tờ bắt buộc có một ô upload riêng, kèm thanh tiến độ kiểu "5/7 giấy tờ".
  - Nút Nộp chỉ bấm được khi đã đủ các ô bắt buộc.
  - Nếu khách thật sự chưa có một giấy tờ, khách chọn "Chưa có, sẽ bổ sung" và ghi lý do. Ô đó được tính là đã xử lý, hồ sơ vẫn nộp được và được gắn cờ cho nhân viên biết trước.
- **Giá trị:** giảm hồ sơ thiếu. Khách chọn đúng ô nên giảm xếp sai loại ngay từ đầu, không cần AI phân loại.
- **Dùng lại hệ thống:** mở rộng chức năng kiểm tra cơ bản của portal; vẫn dùng chức năng lưu nháp sẵn có.

### 4.3 Hướng dẫn chụp ảnh và kiểm tra cơ bản trên điện thoại
- **Làm gì:**
  - Camera hiện khung căn giấy tờ và mẹo chụp (đủ sáng, không lóa, thấy đủ 4 góc).
  - Portal kiểm tra theo quy tắc ngay trên thiết bị: độ phân giải tối thiểu, file mở được, PDF đủ số trang.
  - Khách xem lại ảnh và xác nhận "chữ đọc rõ" trước khi lưu.
- **Giá trị:** giảm tài liệu mờ hoặc hỏng. Phù hợp với 78% hồ sơ bắt đầu trên điện thoại.
- **Dùng lại hệ thống:** portal, các định dạng đang chấp nhận (PDF/JPG/PNG, tối đa 10 MB). Ảnh không gửi ra ngoài môi trường đã duyệt.

### 4.4 Yêu cầu bổ sung gộp một lần
- **Làm gì:**
  - Trên màn hình review, nhân viên đánh dấu các mục thiếu hoặc lỗi ngay trên checklist của hồ sơ.
  - Hệ thống gửi **một email duy nhất** liệt kê đủ các mục cần sửa, kèm link (khách phải đăng nhập) mở thẳng tới đúng ô cần upload lại.
  - Khi khách nộp lại, nhân viên chỉ kiểm lại các mục đó.
- **Giá trị:** giảm thời gian nhân viên cho mỗi ca bổ sung (hiện 10 phút) và rút ngắn thời gian khách sửa hồ sơ.
- **Dùng lại hệ thống:** email giao dịch, portal có đăng nhập, kho lưu tài liệu.

## 5. Quy trình cũ và mới

| Giai đoạn | Hiện tại | Sau khi có MVP |
|---|---|---|
| 1. Tìm hiểu yêu cầu | Đọc thông tin trên website hoặc hỏi tư vấn viên chi nhánh; một số khách khó xác định giấy tờ nào áp dụng cho mình | Trả lời 4–5 câu hỏi, nhận checklist riêng có ảnh mẫu |
| 2. Chuẩn bị và upload | Có hồ sơ thiếu file, file khó đọc hoặc xếp sai loại | Mỗi giấy tờ một ô, có hướng dẫn chụp, kiểm tra cơ bản, thanh tiến độ, chặn nộp mềm |
| 3. Kiểm tra đủ hồ sơ | Nhân viên xem hồ sơ và yêu cầu sửa; khách có thể bị yêu cầu thêm sau khi đã nộp | Hồ sơ đến tay nhân viên đã đủ hơn. Nếu thiếu: đánh dấu trên checklist, gửi một email gộp, chỉ kiểm lại mục đã sửa |
| 4. Theo dõi trạng thái | Không đổi (ngoài phạm vi MVP) | Không đổi |
| 5. Review ban đầu | Không đổi | Hưởng lợi gián tiếp nhờ giấy tờ đã được xếp đúng loại |

## 6. Vì sao giải pháp giải được gốc rễ

| Nguyên nhân gốc | Bằng chứng | Thành phần xử lý |
|---|---|---|
| Không biết cần giấy tờ gì | Yêu cầu thay đổi theo sản phẩm và hồ sơ khách (Section 2); người nộp lần đầu 75% phải bổ sung (Exhibit B) | 4.1 |
| Hệ thống không kiểm tra đủ hồ sơ | Chỉ kiểm tra định dạng và dung lượng (Section 5) | 4.2 |
| Giấy tờ bị xếp sai loại | Section 2, Stage 2 | 4.2 (khách tự chọn đúng ô) |
| Ảnh mờ, khó đọc | Section 2; 78% bắt đầu trên điện thoại, 41% là ảnh chụp hoặc scan (Exhibit A, D) | 4.3 |
| Vòng bổ sung chậm, tốn công | 10 phút mỗi ca; 32% không sửa xong trong 1 ngày (Exhibit A) | 4.4 |

## 7. Product Backlog cho MVP

| Ưu tiên | Item | Giá trị |
|---|---|---|
| 1 | Checklist giấy tờ riêng cho từng khách (4.1) | Xử lý nguyên nhân gốc; nhóm người nộp lần đầu chịu ảnh hưởng lớn nhất |
| 2 | Ô upload theo giấy tờ và chặn nộp mềm (4.2) | Biến checklist thành chốt chặn thật sự, giảm thiếu và xếp sai loại |
| 3 | Yêu cầu bổ sung gộp một lần (4.4) | Xử lý phần hồ sơ vẫn còn thiếu; giảm giờ nhân viên |
| 4 | Hướng dẫn chụp ảnh và kiểm tra cơ bản trên điện thoại (4.3) | Giảm tài liệu khó đọc trên điện thoại |

**Acceptance criterion cho item 1:**
- **Given** khách chọn một tổ hợp sản phẩm vay và hồ sơ doanh nghiệp thuộc phạm vi pilot,
- **When** khách trả lời xong bảng câu hỏi,
- **Then** checklist hiện **đúng 100%** giấy tờ bắt buộc theo bảng quy định nội bộ cho tổ hợp đó, không thiếu, không thừa.
- Kiểm tra trên **tất cả** tổ hợp của pilot và được Credit Operations xác nhận.

> PO có thể đổi thứ tự item 3 và 4 sau khi kiểm chứng giả định ở Sprint 1. Ví dụ: nếu ảnh khó đọc là lý do bổ sung phổ biến nhất, đưa item 4 lên trước.

## 8. Giả định về phạm vi
- **[Giả định]** Pilot chỉ áp dụng cho 1–2 sản phẩm vay SME phổ biến nhất. Như vậy số tổ hợp quy tắc checklist vừa sức test của 1 QA làm 50%.
- **[Giả định]** Bảng quy định giấy tờ nội bộ chuyển được thành bảng quy tắc để portal đọc.
- **[Giả định]** Kiểm tra chất lượng ảnh chạy theo quy tắc trong portal, không gửi ảnh ra ngoài, nên không cần phê duyệt dịch vụ bên thứ ba.

## 9. Để sau MVP

| Tính năng | Lý do hoãn |
|---|---|
| AI tự nhận loại giấy tờ, OCR | Cần phê duyệt bảo mật, chưa chắc xong trong 8 tuần (Section 6); prototype phân loại chỉ đạt 48/50 trên tài liệu sạch, chưa được đánh giá đầy đủ trên ảnh chụp thật (Exhibit D) |
| Dùng lại giấy tờ cũ cho khách quay lại | Cần làm rõ quy tắc hiệu lực và phân quyền truy cập; tác động nhỏ hơn (khoảng 180 ca/tháng) |
| Chatbot AI | Ngoài phạm vi MVP, phê duyệt không chắc kịp (Section 7) |
| Thông báo trạng thái chủ động | Thuộc vấn đề khác (Stage 4); hệ thống trạng thái chỉ xuất dữ liệu 1 lần/ngày (Section 5) |

## 10. Rủi ro chính

| # | Rủi ro | Cách xử lý |
|---|---|---|
| 1 | Quy tắc checklist sai hoặc thiếu: khách bị chặn sai, hoặc vẫn nộp thiếu | Lấy quy tắc từ bảng nội bộ; Credit Operations xác nhận ngay Sprint 1; QA test toàn bộ tổ hợp của pilot; giới hạn pilot ở 1–2 sản phẩm |
| 2 | Giao diện trên điện thoại khó dùng, khách không biết bước tiếp theo | Test usability từ Sprint 2; mỗi màn hình chỉ có một hành động chính |
| 3 | Security review trước pilot bị trễ | Đăng ký lịch review sớm; không dùng dịch vụ mới; tài liệu nằm trong kho lưu trữ hiện có |

## 11. Đo thành công
- **Tỷ lệ hồ sơ pilot phải bổ sung:** từ 65% xuống **≤ 40%**, đo trong 4 tuần đầu pilot, so với hồ sơ ngoài pilot cùng kỳ.
- **Thời gian nhân viên cho mỗi ca bổ sung:** từ 10 phút xuống **≤ 6 phút** **[Giả định]**, đo cùng kỳ.
- **Tác động ước tính [Giả định]:** nếu tỷ lệ giảm từ 65% xuống 40%, mỗi tháng bớt khoảng 300 ca bổ sung, tương đương khoảng **50 giờ nhân viên** (300 × 10 phút).
