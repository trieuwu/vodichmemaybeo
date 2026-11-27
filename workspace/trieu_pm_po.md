# Workspace: Triệu (PM / PO) — CHIA VIỆC 3 NGƯỜI (TRIỆU - TÚ ANH - KHẢI)

> **CẬP NHẬT KHẨN (CHIA 3 NGƯỜI - BỎ QUA ĐĂNG):**
> Do máy của Đăng đang gặp lỗi kỹ thuật, toàn bộ 4 Parts của bài nộp (tối đa 6 trang A4) được chia gọn cho **3 anh em (Triệu, Tú Anh, Khải)** gánh hết để về đích nhanh nhất.
> **Mục tiêu & Giải pháp thống nhất 100% toàn team (hợp nhất bản của Tú Anh & Đăng):**
> - **Tên giải pháp:** **SmartPack – Trải nghiệm Chuẩn bị Hồ sơ "Đủ Ngay Lần Đầu" & Vòng lặp Bổ sung 1 Chạm (Stages 1–3, lan tỏa sang Stages 4–5)**.
> - **Vấn đề trọng tâm duy nhất:** **65% hồ sơ vay SME (780/1.200 đơn/tháng)** bị thiếu, mờ hoặc phân loại sai danh mục phải yêu cầu bổ sung (follow-up), tiêu tốn **130 giờ công/tháng** ($780 \times 10 \text{ phút}$) và góp phần làm thời gian chờ trung vị tới khi hoàn tất Initial Review kéo dài gấp đôi (**8 ngày làm việc** so với **4 ngày** của đơn không cần bổ sung - `Exhibit A`), nặng nhất ở nhóm **SME vay lần đầu (75% lỗi = 600 đơn, chiếm 76,9% tổng ca bổ sung - `Exhibit B`)** trong bối cảnh **78% đơn khởi tạo trên Mobile** và **41% tài liệu là ảnh chụp/scan** (`Exhibit A`, `Exhibit D`).

---

## 📋 I. PHÂN CÔNG CỦA TRIỆU (PM / PO) TRONG ĐỘI HÌNH 3 NGƯỜI

| Phần đảm nhận | Nội dung chi tiết cần hoàn thiện | Định mức trang trong file `.docx` |
| :--- | :--- | :---: |
| **1. Part 1: Problem Identification & Product Goal** *(Trọn vẹn)* | • **1.1. Affected Users & Selected Problem:** SME vay lần đầu (`800 đơn, 75% lỗi`), SME vay lại (`400 đơn, 45% lỗi`), RM/Customer Support và Credit Ops (`Section 2, 3, Exhibit B`).<br>• **1.2. Supporting Evidence:** Bảng chứng minh tại sao chọn bài toán **130 giờ follow-up/tháng** (`Exhibit A`) thay vì 33,3 giờ hỏi trạng thái (`Exhibit C`) hay 84 giờ nhập liệu tay (`Exhibit D` - cần AI chưa duyệt).<br>• **1.3. Product Goal & Key Assumption:** Giảm tỷ lệ bổ sung từ **65% xuống $\le$ 35–40%** trong **Controlled Pilot**; giả định nguyên nhân chính là do quy trình/hướng dẫn thiếu rõ ràng chứ không phải do SME không có giấy tờ (kiểm chứng ngay Sprint 1 bằng cách cùng Credit Ops phân loại 50 ca lỗi mẫu trong khung 2h/tuần). | **~1.0 trang** *(Trang 1)* |
| **2. Part 4 - Mục 4.1: PO Response tại Sprint 2 Review** *(Section 7)* | • **Development 1 (5/8 user không biết bước tiếp theo sau khi tương tác với Increment đầu):** Nhận diện rủi ro usability trên cỡ mẫu nhỏ $\rightarrow$ Đưa hạng mục *"Cải thiện điều hướng 1 nút hành động chính/màn hình (Single Primary CTA) + Hộp hướng dẫn Bước tiếp theo (Next Action Banner)"* lên đầu **Sprint 3** và test lại.<br>• **Development 2 (Stakeholder đòi thêm AI-powered customer assistant trước Pilot):** Dùng quyền quyết định của **Product Owner** (`Section 6`) để **Defer sang Post-MVP**, bảo vệ **Product Goal** và deadline 8 tuần (tránh rủi ro không kịp phê duyệt bảo mật Production AI trong 2 Sprints cuối - `Section 6, 7`), đồng thời dùng chính *Hướng dẫn ngữ cảnh ngay tại từng khe tài liệu + Next Action Banner* ở Sprint 3 để giải quyết nhu cầu hỗ trợ khách hàng của Stakeholder. | **~0.7 trang** *(Đầu Trang 6)* |

*(Lưu ý: Phần **Part 2** và **Part 3.A, 3.B (4 PBIs + 4 Sprints)** do **Tú Anh** phụ trách; Phần **Part 3.A (AC cho PBI #1), 3.C (DoD), 3.D (Risks & Defer)** và **Part 4.2 (2 KPIs + Pre-Pilot Release Condition)** do **Khải** phụ trách).*

---

## 📋 II. PROMPT COPY-PASTE CHO TRIỆU (DÁN THẲNG VÀO AI ĐỂ RA BÀI VIẾT CHUẨN)

```text
Đóng vai một Professional Scrum Product Owner (PSPO) và Chuyên gia Chiến lược Ngân hàng Số. Hãy viết hoàn chỉnh và cực kỳ súc tích 2 phần sau đây cho bài thi Case Study "Bank X – Redesign SME Credit Application Experience" (để ghép vào báo cáo Word tối đa 6 trang A4):
1) Toàn bộ PART 1: PROBLEM IDENTIFICATION & PRODUCT GOAL (~1 trang A4)
2) PART 4 - MỤC 4.1: PRODUCT OWNER RESPONSE TO SPRINT 2 REVIEW DEVELOPMENTS (~0.7 trang A4)

YÊU CẦU BẮT BUỘC VỀ ĐỊNH DẠNG & LẬP LUẬN:
- Trả lời bằng tiếng Việt súc tích, thực tế, ưu tiên bảng biểu (compact tables) và gạch đầu dòng. Tuyệt đối KHÔNG dùng từ sáo rỗng kiểu AI (như Hơn nữa, Tóm lại, đột phá, toàn diện, seamless...).
- Giữ nguyên tiếng Anh cho các thuật ngữ chuẩn Scrum: Product Goal, Sprint Goal, Product Backlog, PBI, Increment, Definition of Done, Acceptance Criteria, MVP, Product Owner, Sprint Review, Controlled Pilot.
- Trích dẫn inline chính xác theo đề bài ở mọi số liệu: (Exhibit A), (Exhibit B), (Exhibit C), (Exhibit D), (Section 2), (Section 3), (Section 5), (Section 6), (Section 7).
- Giải pháp thống nhất của cả nhóm tên là "SmartPack (Đủ Ngay Lần Đầu)" tập trung vào Stages 1–3 (và tạo tác động lan tỏa sang Stages 4–5), gồm 4 PBIs:
  + PBI #1: Dynamic Eligibility-to-Document Wizard (Bộ lọc 4 câu hỏi sinh Checklist cá nhân hóa + đánh dấu giấy tờ pháp lý cũ cho SME vay lại).
  + PBI #2: Slot-Based Upload & Soft-Completeness Gate (Tải file theo từng khe tài liệu bắt buộc để tự phân loại không cần AI + Chặn nộp mềm kèm tùy chọn ngoại lệ "Chưa có/Cần RM hỗ trợ").
  + PBI #3: On-Device Mobile Quality Pre-Check & Visual Guide (Ảnh mẫu Đúng/Sai + Kiểm tra độ mờ/độ phân giải cục bộ trên trình duyệt điện thoại cho 41% file ảnh chụp/scan).
  + PBI #4: Structured Ops Review & One-Click Surgical Fix-Loop (Nhân viên chọn Mã lý do lỗi ngay trên khe tài liệu -> Hệ thống gửi 1 Transactional Email duy nhất kèm Deep-link mở thẳng đúng khe cần nộp lại).

CHI TIẾT NỘI DUNG CẦN VIẾT:

[PHẦN 1: PART 1 - PROBLEM IDENTIFICATION & PRODUCT GOAL]
1.1. Affected Users & Selected Problem:
- Xác định rõ 1 vấn đề trọng tâm duy nhất ở Stages 1–3: Tỷ lệ hồ sơ vay SME bị nộp thiếu, mờ hoặc phân loại sai danh mục ở mức rất cao (65%), gây ra vòng lặp yêu cầu bổ sung (follow-up) thủ công tốn kém cho ngân hàng và kéo dài thời gian chờ của khách hàng.
- Phân tích rõ 4 nhóm đối tượng bị ảnh hưởng (Section 2, Section 3, Exhibit B):
  + Primary customer (First-time SME applicants): 800 đơn/tháng, tới 75% (600 đơn) phải bổ sung (chiếm 76,9% tổng số ca lỗi) do không biết giấy tờ nào áp dụng cho mình.
  + Returning customer (Experienced SME borrowers): 400 đơn/tháng, vẫn có 45% (180 đơn) phải bổ sung -> chứng tỏ lỗi mang tính hệ thống của quy trình nộp chứ không chỉ do khách hàng mới bỡ ngỡ.
  + Relationship Managers (RM) / Customer Support & Credit Operations employees: Mất 130 giờ công/tháng (780 đơn x 10 phút) để liên hệ đòi hồ sơ và kiểm tra lại (Exhibit A), đồng thời hồ sơ đầu vào lộn xộn làm nặng thêm 240 giờ rà soát ban đầu ở Stage 5 (Exhibit D).

1.2. Supporting Evidence & Prioritization Rationale:
- Lập 1 bảng phân tích bằng chứng sắc bén (Tách rõ Số liệu gốc từ Exhibit A–D, Section 5 và Phép tính quy đổi):
  + Chứng minh tại sao ưu tiên bài toán 65% hồ sơ thiếu/lỗi (130 giờ công/tháng - Exhibit A) mang lại giá trị kinh doanh và tính khả thi cao hơn hẳn so với: (a) Stage 4 - Hỏi trạng thái (400 lượt x 5 phút = 33,3 giờ/tháng, chỉ bằng 1/4 công sức của follow-up - Exhibit C), và (b) Stage 5 - Tự động hóa 35% thời gian nhập liệu thủ công (84 giờ/tháng - Exhibit D), vốn đòi hỏi OCR/Production AI chưa được kiểm chứng trên 41% ảnh chụp thực tế và không đảm bảo kịp phê duyệt bảo mật trong 8 tuần (Section 6).
  + Nêu rõ dữ kiện: Median duration tới khi xong Initial Review của đơn có follow-up là 8 ngày làm việc so với 4 ngày của đơn không follow-up (toàn bộ đơn là 7 ngày; 68% đơn lỗi được sửa trong 1 ngày làm việc, tức 32% ~ 250 đơn mất >1 ngày - Exhibit A). Lưu ý đúng tinh thần đề bài: dù có thể còn các yếu tố khác góp phần gây trễ (Exhibit A), việc cắt giảm vòng lặp follow-up ngay trên kênh Mobile (chiếm 78% đơn khởi tạo - Exhibit A) là đòn bẩy trực tiếp nhất để rút ngắn thời gian xử lý.
  + Lưu ý không dùng con số 21.000 app sessions/tháng làm bằng chứng ưu tiên vì đó là lưu lượng của toàn bộ dịch vụ mobile banking (Exhibit C).

1.3. Product Goal & Key Assumption Requiring Validation:
- Phát biểu 1 Product Goal rõ ràng cho khung 8 tuần (4 Sprints) hướng tới Controlled Pilot, kèm mục tiêu đề xuất (Proposed Pilot Targets): giảm tỷ lệ hồ sơ phải follow-up từ 65% xuống <= 35-40% (nhóm SME vay lần đầu từ 75% xuống <= 40-45%) và giảm thời gian nhân viên xử lý mỗi ca follow-up từ 10 phút xuống <= 5-6 phút.
- Phát biểu 1 Key Assumption quan trọng nhất cần validate: Đa số trong 780 ca bổ sung/tháng xuất phát từ các lỗi có thể ngăn chặn bằng hướng dẫn cá nhân hóa và cổng kiểm tra trước khi nộp trên Mobile (không biết cần giấy tờ gì, nộp nhầm khe danh mục, chụp ảnh mờ), chứ không phải do doanh nghiệp thực sự chưa sở hữu giấy tờ pháp lý đó tại thời điểm đăng ký. Nêu cách kiểm chứng sớm ngay trong Sprint 1: BA cùng Credit Ops dùng quỹ tư vấn 2 giờ/tuần (Section 6) phân loại nguyên nhân của 50 hồ sơ phải bổ sung gần nhất để Product Owner tinh chỉnh thứ tự Product Backlog.

[PHẦN 2: PART 4.1 - PRODUCT OWNER RESPONSE TO SPRINT 2 REVIEW DEVELOPMENTS (SECTION 7)]
Lập 1 bảng phân tích quyết định của Product Owner trước 2 diễn biến tại buổi Sprint Review cuối Sprint 2 (khi team vừa demo Increment gồm PBI #1 Wizard và PBI #2 Slot-Based Upload):
- Development 1 (5/8 người dùng trong buổi đánh giá usability không hiểu phải thực hiện thao tác gì tiếp theo sau khi tương tác với Increment đầu):
  + Đánh giá bằng chứng: Mẫu 8 người là nhỏ nên chưa thể khái quát hóa đại trà, nhưng 5/8 là tín hiệu rủi ro usability nghiêm trọng trên Mobile (78% traffic). Nếu khách hàng tải file vào khe xong mà không biết bước tiếp theo phải làm gì, họ sẽ bỏ dở đơn và làm thất bại Product Goal.
  + Hành động Adaptation trên Product Backlog: Đưa ngay hạng mục sửa lỗi điều hướng UI/UX (Thiết kế mỗi màn hình chỉ có 1 nút hành động chính Single Primary CTA + Thanh trạng thái "Bước tiếp theo của bạn / Next Action Banner" + Micro-copy hướng dẫn rõ ràng) lên đầu Sprint 3, và dùng khung 2 giờ/tuần của Bank Ops (Section 6) để kiểm thử lại (re-test) với nhóm người dùng mới.
- Development 2 (Stakeholder cấp cao yêu cầu bổ sung "AI-powered customer assistant" trước đợt Pilot 8 tuần):
  + Quyết định của Product Owner: Sử dụng Decision authority (Section 6) để từ chối đưa Production AI Customer Assistant vào phạm vi 2 Sprints còn lại (Defer sang Post-MVP Product Backlog).
  + Lập luận bảo vệ Product Goal, Deadline & Capacity: (1) Phê duyệt bảo mật và tuân thủ cho tích hợp AI mới không đảm bảo hoàn tất trong 2 Sprints cuối (Section 6, Section 7) -> nguy cơ chặn đứng lịch ra mắt Controlled Pilot; (2) Capacity cố định (2 Developers, 1 BA, 0.5 QA ~ 5 ngày/Sprint) đang phải tập trung sửa lỗi usability cốt lõi của Development 1 và hoàn thiện PBI #3, PBI #4 cùng Security Review.
  + Giải pháp thay thế thông minh thuyết phục Stakeholder: Chỉ ra rằng nhu cầu thực sự của Stakeholder ("giúp khách hàng không bị bỡ ngỡ khi làm hồ sơ") đã được giải quyết ngay trong Sprint 3 bằng bộ Hướng dẫn ảnh mẫu Đúng/Sai tại từng khe tài liệu, cơ chế chuyển tiếp ngoại lệ có ngữ cảnh cho RM, và thanh dẫn dắt "Bước tiếp theo" (vừa sửa ở Development 1) mà hoàn toàn không cần rủi ro chờ phê duyệt AI.
```

---

## ✍️ III. BẢN NHÁP ĐÃ ĐIỀN SẴN CHO TRIỆU (CÓ THỂ DÙNG NGAY HOẶC PARAPHRASE THÊM)

### PART 1: PROBLEM IDENTIFICATION & PRODUCT GOAL

#### 1.1. Affected Users & Selected Problem
* **Vấn đề trọng tâm được lựa chọn (Stages 1–3):** **65% hồ sơ đăng ký tín dụng SME (780/1.200 đơn/tháng)** bị nộp thiếu, hình ảnh mờ không đọc được hoặc phân loại sai danh mục ngay từ khâu chuẩn bị và tải lên, kéo theo vòng lặp yêu cầu bổ sung (follow-up) thủ công tốn kém và làm chậm tiến độ xử lý hồ sơ (`Section 2`, `Exhibit A`).
* **Các nhóm người dùng và bên liên quan bị ảnh hưởng trực tiếp (`Section 2`, `Section 3`, `Exhibit B`):**
  * **Primary Customer (First-time SME applicants – 800 đơn/tháng):** Thiếu kinh nghiệm về thủ tục ngân hàng và gặp khó khăn khi quy định giấy tờ thay đổi theo từng gói vay/hồ sơ doanh nghiệp (`Section 2`), dẫn tới tỷ lệ phải bổ sung lên đến **75% (600 đơn/tháng)** — chiếm **76,9%** tổng số ca lỗi toàn ngân hàng (`Exhibit B`).
  * **Returning Customer (Experienced SME borrowers – 400 đơn/tháng):** Dù đã từng vay nhưng vẫn có tới **45% (180 đơn/tháng)** phải bổ sung hồ sơ (`Exhibit B`). Điều này chứng minh lỗi xuất phát từ **thiết kế quy trình nộp thiếu kiểm soát trên cổng trực tuyến**, chứ không chỉ do khách hàng mới bỡ ngỡ.
  * **Relationship Managers (RM) / Customer Support & Credit Operations (Credit Ops):** Tốn **130 giờ công/tháng** ($780 \text{ đơn} \times 10 \text{ phút/ca}$) chỉ để liên hệ khách hàng và kiểm tra lại tài liệu nộp bù (`Exhibit A`); đồng thời việc nhận các bộ file lộn xộn làm tăng gánh nặng cho **240 giờ công/tháng** ở khâu rà soát ban đầu (`Exhibit D`).

#### 1.2. Supporting Evidence & Prioritization Rationale

| Nhóm bằng chứng | Dữ kiện gốc từ Case Study (Facts) | Suy luận định lượng (Reasonable Deductions) | Lý do ưu tiên Stages 1–3 thay vì Stage 4 hay Stage 5 |
| :--- | :--- | :--- | :--- |
| **1. Gánh nặng vận hành lớn nhất toàn hành trình** *(`Exhibit A`, `B`, `C`, `D`)* | • **780/1.200 đơn (65%)** phải follow-up; **10 phút/ca**.<br>• Hỏi trạng thái (Stage 4): **400 lượt/tháng**, **5 phút/lượt** (`Exhibit C`).<br>• Initial review (Stage 5): **240 giờ/tháng**, **35%** là nhập liệu tay (`Exhibit D`). | • Follow-up tiêu tốn $780 \times 10 \text{ phút} = \mathbf{130 \text{ giờ công/tháng}}$ (`Exhibit A`).<br>• Trả lời trạng thái chỉ tốn $400 \times 5 \text{ phút} = \mathbf{33,3 \text{ giờ/tháng}}$ (`Exhibit C`).<br>• Nhập liệu tay tốn $240 \times 35\% = \mathbf{84 \text{ giờ/tháng}}$ (`Exhibit D`). | **130 giờ công follow-up/tháng** lớn gấp **~4 lần** công sức trả lời trạng thái ($33,3\text{h}$). Trong khi đó, bài toán $84\text{h}$ nhập liệu tay ở Stage 5 đòi hỏi công nghệ OCR/AI chưa được kiểm chứng trên ảnh chụp thực tế và đối mặt rủi ro không kịp duyệt bảo mật trong 8 tuần (`Section 6`). |
| **2. Kéo dài gấp đôi thời gian xử lý trung vị** *(`Exhibit A`)* | • Median duration tới khi xong Initial Review: Toàn bộ **7 ngày làm việc**; Không follow-up: **4 ngày**; Có follow-up: **8 ngày**.<br>• **68%** đơn lỗi sửa trong 1 ngày làm việc. | • Có **32% đơn lỗi (~250 đơn/tháng)** mất $>1$ ngày làm việc để khách nộp bù.<br>• Đơn bị follow-up có thời gian xử lý trung vị dài gấp đôi (**+4 ngày làm việc**). | Dù `Exhibit A` lưu ý có thể còn yếu tố khác cùng gây trễ (nên không giả định tự động tiết kiệm trọn 4 ngày), việc cắt giảm vòng lặp follow-up là đòn bẩy trực tiếp nhất để kéo thời gian chờ từ 8 ngày hướng về mốc 4 ngày, đồng thời gián tiếp giảm nhu cầu gọi hỏi trạng thái lặp lại (26% hỏi lặp trong 7 ngày - `Exhibit C`). |
| **3. Lỗ hổng kiểm soát trên Mobile & Ảnh chụp** *(`Exhibit A`, `D`, `Section 5`)* | • **78%** đơn khởi tạo trên Mobile (`Exhibit A`).<br>• **41%** tài liệu là ảnh chụp/bản scan (`Exhibit D`).<br>• *Basic validation* chỉ check đuôi file (PDF/JPG/PNG) & dung lượng $\le 10\text{MB}$ (`Section 5`). | • Khoảng **936 đơn/tháng** bắt đầu trên điện thoại, nhưng Portal hoàn toàn chưa kiểm tra tính đầy đủ của bộ hồ sơ cũng như độ rõ nét của 41% tài liệu ảnh chụp trước khi cho nộp. | Giải pháp bắt buộc phải ưu tiên **Mobile-First** và đặt chốt chặn chất lượng ngay tại nguồn (Stages 1–2) mà không phụ thuộc vào *AI Classification Prototype* (vốn mới chỉ đạt 48/50 trên file kỹ thuật số sạch - `Exhibit D`). |

#### 1.3. Product Goal & Key Assumption Requiring Validation
* **Product Goal:**
  > Trong 8 tuần (4 Sprints), chuyển giao giải pháp **SmartPack ("Đủ Ngay Lần Đầu")** trên nền tảng Portal/Mobile sẵn có cho đợt **Controlled Pilot**, giúp khách hàng SME biết chính xác giấy tờ cần nộp, tải tài liệu đạt chuẩn vào đúng khe danh mục và xử lý bổ sung trong 1 chạm, hướng tới mục tiêu đề xuất (**Proposed Pilot Targets**): giảm tỷ lệ hồ sơ phải follow-up từ **65% xuống $\le$ 35–40%** (nhóm SME vay lần đầu từ **75% xuống $\le$ 45%**) và giảm thời gian nhân viên xử lý mỗi ca bổ sung từ **10 phút xuống $\le$ 5–6 phút**.
* **Key Assumption Requiring Validation:**
  * **Giả thuyết cần kiểm chứng:** Phần lớn trong số 780 ca bổ sung/tháng xuất phát từ các lỗi quy trình mà giải pháp hướng dẫn và kiểm tra trước khi nộp trên Mobile có thể ngăn chặn được (*không biết cần giấy tờ nào, gắn sai danh mục, hoặc chụp ảnh bị mờ/thiếu trang*), chứ không phải do doanh nghiệp thực sự *chưa sở hữu giấy tờ đó* tại thời điểm đăng ký.
  * **Cơ chế kiểm chứng sớm ngay tại Sprint 1:** BA phối hợp với Credit Operations sử dụng quỹ thời gian tư vấn **2 giờ/tuần** (`Section 6`) để phân loại nguyên nhân gốc trên mẫu **50 hồ sơ phải follow-up gần nhất**, giúp **Product Owner** điều chỉnh thứ tự ưu tiên của **Product Backlog** dựa trên bằng chứng thực tế.

---

### PART 4.1: PRODUCT OWNER RESPONSE TO SPRINT 2 REVIEW DEVELOPMENTS (`Section 7`)

| Diễn biến tại Sprint 2 Review (`Section 7`) | Quyết định của Product Owner (Inspection & Adaptation) | Bảo vệ Product Goal & Tác động lên Kế hoạch Sprint 3–4 |
| :--- | :--- | :--- |
| **Development 1: Unexpected User Feedback**<br>*5/8 người dùng mục tiêu gặp khó khăn không hiểu phải thực hiện thao tác gì tiếp theo sau khi tương tác với Increment đầu tiên (mẫu nhỏ).* | **1. Inspect (Đánh giá khách quan):** Mẫu 8 người là nhỏ nên chưa thể khái quát hóa đại trà, nhưng 5/8 người lúng túng là tín hiệu rủi ro usability nghiêm trọng trên giao diện Mobile (78% traffic - `Exhibit A`).<br>**2. Adapt (Điều chỉnh Product Backlog):** Đưa ngay hạng mục **"Tối ưu điều hướng hành động kế tiếp (Single Primary CTA, Thanh trạng thái Next-Action Banner & Micro-copy chỉ dẫn)"** lên đầu **Sprint 3** trước khi mở rộng các tính năng tiếp theo. | • **Bảo vệ Product Goal:** Nếu người dùng hoàn tất bước chọn Checklist hoặc tải file vào khe mà bị khựng lại không biết bước tiếp theo phải bấm vào đâu, họ sẽ bỏ dở đơn hoặc nộp lỗi, làm thất bại mục tiêu giảm tỷ lệ follow-up xuống $\le 35–40\%$.<br>• **Kế hoạch Sprint 3–4:** Dành 2–3 ngày đầu Sprint 3 để 2 Developers và BA tinh chỉnh luồng chuyển bước trên Mobile, sau đó dùng ngay khung **2 giờ/tuần** của Bank Ops (`Section 6`) để kiểm thử lại (re-test) với nhóm người dùng mới. |
| **Development 2: New Stakeholder Request**<br>*Stakeholder cấp cao yêu cầu thêm "AI-powered customer assistant" trước đợt Pilot 8 tuần (ngoài scope MVP, chưa chắc kịp duyệt AI).* | **1. Quyết định phạm vi (Scope Decision):** Dùng *Decision authority* của **Product Owner** (`Section 6`) để **từ chối đưa Production AI Customer Assistant vào 2 Sprints cuối (Defer sang Post-MVP Product Backlog)**.<br>**2. Giải pháp thay thế đáp ứng nhu cầu cốt lõi:** Giải thích với Stakeholder rằng nhu cầu giúp khách hàng được hướng dẫn tức thì trong quá trình làm hồ sơ sẽ được đáp ứng ngay ở Sprint 3–4 thông qua **Hướng dẫn ảnh mẫu Đúng/Sai tại từng khe tài liệu**, **Thanh chỉ dẫn Next-Action Banner** (vừa bổ sung từ Development 1) và **Chốt chuyển tiếp ngoại lệ có ngữ cảnh cho RM**. | • **Bảo vệ Product Goal, Deadline & Compliance:** Phê duyệt bảo mật cho tích hợp Production AI mới **không đảm bảo hoàn tất trong 2 Sprints còn lại** (`Section 6`, `Section 7`); nếu cố làm sẽ gây nguy cơ vỡ deadline Pilot 8 tuần và làm quá tải capacity cố định (2 Developers, 1 BA, 0.5 QA đang phải xử lý lỗi usability của Development 1, hoàn thiện PBI #3–#4 và chuẩn bị **Security Review** ở Sprint 4).<br>• **Lộ trình Post-MVP:** Đưa *AI Customer Assistant* vào lộ trình đánh giá sau Pilot để xin phê duyệt bảo mật song song khi đã có dữ liệu vận hành thực tế. |
