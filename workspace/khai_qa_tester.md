# Workspace: Khải (QA / Tester) — CHIA VIỆC 3 NGƯỜI (TRIỆU - TÚ ANH - KHẢI)

> **CẬP NHẬT KHẨN (CHIA 3 NGƯỜI - BỎ QUA ĐĂNG):**
> Do máy của Đăng đang gặp lỗi kỹ thuật, toàn bộ 4 Parts của bài nộp (tối đa 6 trang A4) được chia gọn cho **3 anh em (Triệu, Tú Anh, Khải)**.
> **Khải sẽ nhận thêm mục 3.D (Risks & Defer) từ phần của Đăng** (vốn rất sát với chuyên môn QA, Rủi ro & Kiểm thử bảo mật), trong khi **Tú Anh** nhận phần bảng 4 PBIs & 4 Sprints (3.A & 3.B).
> **Tên giải pháp thống nhất toàn team:** **SmartPack – Trải nghiệm Chuẩn bị Hồ sơ "Đủ Ngay Lần Đầu" & Vòng lặp Bổ sung 1 Chạm (Stages 1–3)**.

---

## 📋 I. PHÂN CÔNG CỦA KHẢI (QA / TESTER) TRONG ĐỘI HÌNH 3 NGƯỜI

| Phần đảm nhận | Nội dung chi tiết cần hoàn thiện | Định mức trang trong file `.docx` |
| :--- | :--- | :---: |
| **1. Part 3 - Mục 3.A (Bổ sung):** Acceptance Criterion cho PBI #1 | • Viết **01 Specific, Testable Acceptance Criterion** (theo chuẩn *Given – When – Then*) cho PBI có độ ưu tiên cao nhất (**PBI #1: Dynamic Eligibility-to-Document Wizard / Bộ lọc sinh Checklist cá nhân hóa**). | **~0.2 trang** *(Giữa Trang 4)* |
| **2. Part 3 - Mục 3.C:** Definition of Done (DoD) | • Viết **04 điều kiện chất lượng (Quality Conditions)** bắt buộc cho mọi Usable Increment: (1) Code & Mobile Compatibility (78% traffic - `Exhibit A`), (2) Security & Approved Storage (`Section 6`), (3) QA Testing trong định mức 50% capacity (~5 ngày/Sprint - `Section 6`), (4) Business Rule Sign-off cùng Bank Ops (trong khung $\le$ 2 giờ/tuần - `Section 6`). | **~0.4 trang** *(Đầu Trang 5)* |
| **3. Part 3 - Mục 3.D:** Feasibility, Risks & Deferred Feature *(Nhận từ Đăng)* | • **3 Rủi ro / Phụ thuộc xếp theo độ quan trọng giảm dần** (Risk #1: Nút thắt Bank Ops chỉ có 2h/tuần & QA 50% capacity khi kiểm thử ma trận quy tắc checklist; Risk #2: Độ biến thiên của 41% ảnh chụp thực tế trên Mobile; Risk #3: Tiến độ Security Review trước Pilot) + **Cách quản trị chi tiết cho Risk #1**.<br>• **Tính năng Defer sau MVP & Lý do:** Hoãn đưa *AI Document Classification Prototype (96% trên 50 file sạch) & OCR Auto-Transcription (35% thời gian review - `Exhibit D`)* cũng như *AI Customer Assistant (`Section 7`)* lên Production. | **~0.7 trang** *(Cuối Trang 5)* |
| **4. Part 4 - Mục 4.2:** Validation Metrics & Pre-Pilot Release Condition | • **02 Measurable Success Indicators (KPIs)** có đầy đủ *Current Baseline – Proposed Pilot Target – Evaluation Period (4 tuần Controlled Pilot)*.<br>• **01 Critical Test / Release Condition** bắt buộc hoàn tất trước khi mở **Controlled Pilot** (`Section 6`: Security Review + Mobile E2E Critical Functionality Testing). | **~0.6 trang** *(Cuối Trang 6)* |

---

## 📋 II. PROMPT COPY-PASTE CHO KHẢI (DÁN THẲNG VÀO AI ĐỂ RA BÀI VIẾT CHUẨN)

```text
Đóng vai một Agile QA Lead / Scrum Team Member và Chuyên gia Kiểm thử & Quản trị Rủi ro Ngân hàng Số. Hãy viết hoàn chỉnh, sắc bén và súc tích các mục sau đây cho bài thi Case Study "Bank X – Redesign SME Credit Application Experience" (để ghép vào báo cáo Word tối đa 6 trang A4):
1) PART 3 - MỤC 3.A (BỔ SUNG): 01 Specific, Testable Acceptance Criterion cho PBI #1 (Highest Priority).
2) PART 3 - MỤC 3.C: Definition of Done (DoD) gồm 4 điều kiện chất lượng.
3) PART 3 - MỤC 3.D: Feasibility and Scope (Bảng 3 Rủi ro/Phụ thuộc xếp theo thứ tự quan trọng giảm dần kèm cách quản trị chi tiết cho Rủi ro số 1 + 1 nhóm tính năng Defer sau MVP kèm lý do).
4) PART 4 - MỤC 4.2: Validation & Release Gate (Bảng 2 Measurable Success Indicators có Baseline, Target, Evaluation Period + 1 Critical Test/Release Condition trước Controlled Pilot).

YÊU CẦU BẮT BUỘC VỀ ĐỊNH DẠNG & LẬP LUẬN:
- Trả lời bằng tiếng Việt súc tích, thực tế, ưu tiên bảng biểu (compact tables) và gạch đầu dòng. Không dùng từ ngữ quảng cáo sáo rỗng kiểu AI.
- Giữ nguyên tiếng Anh cho các thuật ngữ chuẩn Scrum: Product Goal, Sprint Goal, Product Backlog, PBI, Increment, Definition of Done, Acceptance Criteria, MVP, Product Owner, Sprint Review, Controlled Pilot.
- Trích dẫn inline chính xác theo đề bài ở mọi số liệu và ràng buộc: (Exhibit A), (Exhibit B), (Exhibit C), (Exhibit D), (Section 5), (Section 6), (Section 7).
- Bám sát giải pháp thống nhất của cả nhóm là "SmartPack (Đủ Ngay Lần Đầu)" tại Stages 1–3, với 4 PBIs:
  + PBI #1 (Highest Priority): Dynamic Eligibility-to-Document Wizard (Bộ lọc 4 câu hỏi sinh Checklist giấy tờ cá nhân hóa theo gói vay/loại hình SME từ bảng quy định nội bộ + đánh dấu tái sử dụng giấy tờ pháp lý cũ cho SME vay lại).
  + PBI #2: Slot-Based Upload & Soft-Completeness Gate (Mỗi giấy tờ 1 ô upload riêng tự động gắn nhãn danh mục vào Document storage + Chặn nộp mềm kèm tùy chọn ngoại lệ "Chưa có, sẽ bổ sung / Cần RM hỗ trợ").
  + PBI #3: On-Device Mobile Quality Pre-Check & Visual Guide (Ảnh mẫu Đúng/Sai + Kiểm tra độ mờ/độ phân giải cục bộ trên trình duyệt Mobile cho 41% file ảnh chụp/scan).
  + PBI #4: Structured Ops Review & One-Click Surgical Fix-Loop (Nhân viên chọn Mã lý do lỗi ngay trên khe tài liệu -> gửi 1 Transactional Email duy nhất kèm Deep-link mở thẳng tới đúng ô cần nộp lại).

CHI TIẾT NỘI DUNG CẦN VIẾT:

1. Acceptance Criterion cho PBI #1 (Part 3.A):
- Viết theo cấu trúc Given - When - Then thật cụ thể, kiểm thử được (testable): Khi khách hàng SME đăng nhập trên Mobile/Web và chọn một tổ hợp sản phẩm vay + loại hình doanh nghiệp + trạng thái khách mới/cũ thuộc phạm vi Controlled Pilot (giới hạn 1–2 sản phẩm vay phổ biến nhất để vừa sức test), hệ thống phải hiển thị chính xác 100% các khe giấy tờ bắt buộc theo ma trận quy định nội bộ (Section 5) trong < 2 giây, không thừa không thiếu, lưu vào bản nháp (Draft) và được đại diện Credit Operations xác nhận.

2. Definition of Done (Part 3.C):
- Đề xuất 4 điều kiện chất lượng bắt buộc cho mọi Usable Increment mỗi Sprint:
  (1) Functional & Mobile-First Readiness (vượt qua Unit Test và 100% Acceptance Criteria trên cả Web và Mobile browser cho 78% traffic di động - Exhibit A);
  (2) Security & Approved Infrastructure Compliance (100% tài liệu tải vào các Slot và luồng Deep-link nằm trong Document storage được phê duyệt, kiểm soát phân quyền chặt chẽ, không gọi API bên thứ ba chưa duyệt - Section 5, Section 6);
  (3) QA Verification within Fixed 50% Capacity (hoàn tất kiểm thử tích hợp và hồi quy trong quỹ 5 ngày làm việc/Sprint của QA với 0 lỗi Critical/High - Section 6);
  (4) Business Rule Alignment & PO Sign-off (đối chiếu đúng quy định nội bộ cùng Credit Ops trong khung <= 2 giờ/tuần và được Product Owner nghiệm thu - Section 6).

3. Feasibility and Scope (Part 3.D):
- Lập bảng 3 Rủi ro / Phụ thuộc triển khai xếp theo thứ tự quan trọng từ #1 đến #3:
  + Risk #1 (Most Critical): Nút thắt thời gian tham vấn của Bank Ops (tối đa 2 giờ/tuần) và QA bán thời gian (50% ~ 5 ngày/Sprint) khi phải chuẩn hóa và kiểm thử các tổ hợp quy tắc Checklist (Section 6). Trình bày thật chi tiết cách quản trị Risk #1: (a) Giới hạn phạm vi Controlled Pilot ở 1–2 sản phẩm vay SME phổ biến nhất [Giả định hợp lý]; (b) BA soạn sẵn bảng nháp quy tắc từ tài liệu nội bộ (Section 5) trước buổi họp để 2 giờ/tuần của Ops chỉ dùng cho việc xác nhận ngoại lệ và usability test; (c) Dev viết Unit Test tự động cho bộ rule và bàn giao cuốn chiếu từ giữa Sprint để 5 ngày của QA không bị nghẽn vào ngày cuối.
  + Risk #2: Độ biến thiên của 41% tài liệu ảnh chụp/scan thực tế trên điện thoại (Exhibit D) dễ gây chặn nhầm (False Positive). Cách giảm thiểu: Dùng cảnh báo mềm (Soft Warning) kèm bước khách hàng tự tick xác nhận "Chữ trên ảnh đọc rõ" thay vì chặn cứng tuyệt đối.
  + Risk #3: Nguy cơ trễ hạn Security Review bắt buộc trước Controlled Pilot (Section 6). Cách giảm thiểu: Tái sử dụng 100% cơ chế xác thực Portal, Document storage và Transactional email hiện hữu (Section 5); mời đội Security rà soát cơ chế phân quyền Deep-link ngay từ Sprint 3.
- Nêu rõ tính năng Defer sau MVP & Lý do: Hoãn tích hợp AI Document Classification Prototype (96% trên 50 file digital sạch) & OCR tự động hóa 35% thời gian nhập liệu tay ở Stage 5 (Exhibit D), cũng như AI Customer Assistant (Section 7). Giải thích rõ: Prototype chưa được đánh giá trên 41% ảnh chụp/scan thực tế hay file lỗi (Exhibit D), và phê duyệt bảo mật/compliance cho Production AI không đảm bảo hoàn tất trong 8 tuần (Section 6, Section 7).

4. Measurable Success Indicators & Pre-Pilot Release Condition (Part 4.2):
- Lập bảng 2 Measurable Success Indicators (KPIs) có đầy đủ Current Baseline (trích dẫn Exhibit A, B), Proposed Pilot Target, và Evaluation Period (đo trong 4 tuần đầu của Controlled Pilot so với nhóm hồ sơ đối chứng ngoài Pilot cùng kỳ):
  + KPI 1: Tỷ lệ hồ sơ trong Controlled Pilot phải yêu cầu bổ sung (Missing-Document Follow-up Rate): giảm từ baseline 65% toàn bộ (75% ở SME vay lần đầu - Exhibit A, B) xuống mục tiêu đề xuất <= 35–40% toàn bộ (<= 45% ở SME vay lần đầu), kèm chỉ số bảo vệ (Guardrail) là tỷ lệ hoàn tất nộp đơn trên Mobile không bị sụt giảm.
  + KPI 2: Thời gian nhân viên xử lý trung bình cho mỗi ca bổ sung (Average Staff Time per Follow-up) nhờ luồng One-Click Surgical Fix-Loop: giảm từ baseline 10 phút/ca (tương đương 130 giờ/tháng - Exhibit A) xuống mục tiêu đề xuất <= 5–6 phút/ca, đồng thời theo dõi tỷ lệ khách sửa xong trong 1 ngày làm việc tăng từ 68% lên >= 80% và median duration dịch chuyển từ 7 ngày hướng về <= 5 ngày làm việc (Exhibit A).
- Viết 1 Critical Test / Release Condition bắt buộc trước Controlled Pilot (Section 6): Cổng kiểm soát kép gồm (1) Mandatory Security & Access Control Review (đảm bảo 100% file tải theo Slot và Deep-link nộp bù yêu cầu đăng nhập xác thực, lưu trong Document storage được phê duyệt, không rò rỉ dữ liệu chéo giữa các tài khoản SME) và (2) End-to-End Critical Functionality Testing trên thiết bị Mobile đạt 100% Pass Rate (0 lỗi Critical/High) trên toàn bộ tổ hợp quy tắc của các gói vay trong Pilot.
```

---

## ✍️ III. BẢN NHÁP ĐÃ ĐIỀN SẴN CHO KHẢI (CÓ THỂ DÙNG NGAY HOẶC PARAPHRASE THÊM)

### PART 3.A (BỔ SUNG): ACCEPTANCE CRITERION CHO PBI #1 (HIGHEST PRIORITY)
* **Specific, Testable Acceptance Criterion cho PBI #1 (*Dynamic Eligibility-to-Document Wizard*):**
  > **Given** một khách hàng SME đã đăng nhập vào *Online application portal* trên trình duyệt Mobile (`Section 5`) và chọn một tổ hợp *(Sản phẩm vay + Loại hình doanh nghiệp + Trạng thái khách vay lần đầu/vay lại)* thuộc phạm vi **Controlled Pilot**,
  > **When** khách hàng hoàn tất 4 câu hỏi phân loại và bấm xác nhận,
  > **Then** hệ thống hiển thị chính xác **100%** danh sách các khe giấy tờ bắt buộc tương ứng với bảng quy định tài liệu nội bộ của Bank X (`Section 5`) trong thời gian phản hồi $< 2$ giây (không hiển thị thừa giấy tờ không áp dụng, không bỏ sót giấy tờ bắt buộc), tự động lưu cấu hình vào bản nháp (*Draft*), và kết quả ánh xạ này vượt qua 100% kịch bản kiểm thử tổ hợp được đại diện **Credit Operations** xác nhận.

---

### PART 3.C: DEFINITION OF DONE (DoD)
Mọi **Product Backlog Item (PBI)** chỉ được công nhận là hoàn thành và đủ điều kiện tích hợp vào **Usable Increment** cuối mỗi Sprint khi thỏa mãn đồng thời 4 tiêu chí chất lượng sau:
1. **Functional & Mobile-First Compatibility:** Code đã được peer-review giữa 2 Developers, vượt qua 100% Unit Tests tự động và thỏa mãn toàn bộ **Acceptance Criteria** trên cả trình duyệt Web và thiết bị di động (đáp ứng **78% hồ sơ khởi tạo trên Mobile** và các định dạng chuẩn PDF, JPG/JPEG, PNG $\le 10\text{MB}$ – `Exhibit A`, `Section 5`).
2. **Security & Approved Environment Compliance (`Section 6`):** Toàn bộ tài liệu tải lên qua từng Slot và luồng truy cập *Deep-link* bổ sung hồ sơ được lưu trữ và phân quyền hoàn toàn bên trong **Document storage** được phê duyệt của Bank X; kiểm tra xác thực phiên đăng nhập hợp lệ và tuyệt đối không gửi dữ liệu khách hàng ra dịch vụ bên thứ ba hay mô hình AI chưa được cấp phép.
3. **Quality Assurance within Fixed 50% QA Capacity (`Section 6`):** Đã được QA Engineer thực hiện kiểm thử chức năng, kiểm thử biên và kiểm thử hồi quy (trong định mức **5 ngày làm việc/Sprint**) với **0 lỗi mức độ Critical hoặc High-severity** còn tồn đọng.
4. **Operational Rule Sign-off & PO Acceptance:** Logic hiển thị danh mục hồ sơ và mã lý do yêu cầu bổ sung đã được đối chiếu khớp với quy định nội bộ cùng đại diện **Bank Operations** (trong khung tham vấn tối đa **2 giờ/tuần** – `Section 6`) và được **Product Owner** nghiệm thu.

---

### PART 3.D: FEASIBILITY, RISK MANAGEMENT & DEFERRED SCOPE

#### 1. Key Implementation Dependencies / Risks (Ranked 1–3) & Mitigation for #1

| Hạng | Rủi ro / Phụ thuộc triển khai (Risk / Dependency) | Tác động tới Dự án | Chiến lược Quản trị & Giảm thiểu (Mitigation Plan) |
| :---: | :--- | :--- | :--- |
| **#1**<br>*(Most Critical)* | **Nút thắt thời gian tham vấn của Bank Ops (tối đa 2 giờ/tuần) & QA Engineer bán thời gian (50% ~ 5 ngày/Sprint) khi chuẩn hóa và kiểm thử quy tắc Checklist** *(`Section 6`)* | Nếu quy tắc checklist bị sai/thiếu hoặc dồn việc test vào cuối Sprint, khách hàng sẽ bị chặn nộp nhầm hoặc vẫn nộp thiếu, đồng thời đội dự án không kịp hoàn tất kiểm thử trong 8 tuần. | **Kế hoạch quản trị chi tiết cho Risk #1:**<br>• **Khoanh vùng phạm vi Pilot thông minh [Giả định hợp lý]:** Giới hạn **Controlled Pilot** ở **1–2 sản phẩm vay SME phổ biến nhất** để số lượng nhánh quy tắc vừa khít năng lực kiểm thử 100% tổ hợp của 1 QA làm 50% thời gian.<br>• **Kỷ luật sử dụng 2 giờ/tuần của Bank Ops:** BA tự trích xuất trước ma trận quy định giấy tờ lưu nội bộ (`Section 5`) thành bảng rule nháp và mockup màn hình *trước* buổi họp; quỹ **2 giờ/tuần** của RM & Credit Ops chỉ dùng để **xác nhận các ca ngoại lệ, phân loại nhanh 50 ca lỗi mẫu ở Sprint 1 và chạy usability test**, không dùng để họp lấy yêu cầu từ đầu.<br>• **Bàn giao cuốn chiếu & Tự động hóa cho 5 ngày QA:** 2 Developers viết Unit Test tự động cho toàn bộ tập rule của *Dynamic Wizard* và bàn giao từng phần từ ngày thứ 4 của Sprint để QA rải đều 5 ngày công, tránh dồn ứ vào cuối Sprint. |
| **#2**<br>*(High)* | **Độ biến thiên của 41% tài liệu ảnh chụp/scan thực tế gây cảnh báo mờ nhầm (False Positive)** *(`Exhibit D`)* | Nếu bộ kiểm tra ảnh cục bộ trên Mobile chặn cứng quá gắt, khách hàng chụp trong điều kiện ánh sáng thường có thể bị kẹt không nộp được đơn. | Áp dụng cơ chế **Chặn cứng về cấu trúc – Cảnh báo mềm về hình ảnh**: Chặn cứng khi sai định dạng, vượt $10\text{MB}$ (`Section 5`) hoặc bỏ trống khe bắt buộc mà không chọn lý do ngoại lệ; nhưng với độ mờ/độ sáng, hệ thống hiển thị **Cảnh báo mềm (Soft Warning)** kèm ảnh mẫu đối chiếu và cho phép khách hàng tick xác nhận *"Tôi đã kiểm tra chữ trên ảnh đọc rõ"* để tiếp tục nộp. |
| **#3**<br>*(Medium)* | **Nguy cơ trễ tiến độ Security Review bắt buộc trước khi mở Controlled Pilot** *(`Section 6`)* | Dù code xong đúng hạn 4 Sprints nhưng không được phép mở Pilot cho khách hàng thật. | Tái sử dụng 100% hạ tầng xác thực của *Online application portal*, *Document storage* và *Transactional emails* sẵn có (`Section 5`); không tích hợp dịch vụ bên thứ ba; đăng ký lịch rà soát bảo mật sớm ngay từ cuối Sprint 2 và đóng băng tính năng (feature freeze) ở nửa cuối Sprint 4. |

#### 2. Features Deferred Beyond MVP & Justification
* **Tính năng hoãn sau MVP (Deferred to Post-MVP):**
  1. **Đưa AI Document Classification Prototype (đạt 96% trên 50 file sạch) lên Production và dùng OCR/AI tự động hóa 35% thời gian nhập liệu thủ công (84 giờ/tháng) ở Stage 5** (`Exhibit D`, `Section 5`).
  2. **AI-powered Customer Assistant** theo yêu cầu phát sinh tại Sprint 2 Review (`Section 7`).
* **Lý do chiến lược (Why Defer):**
  * **Rủi ro kỹ thuật & dữ liệu chưa kiểm chứng:** Bản AI prototype của ngân hàng mới chỉ thử nghiệm trên 50 tài liệu kỹ thuật số sạch, **chưa được kiểm chứng trên 41% ảnh chụp/scan thực tế, file lỗi hoặc hồ sơ nộp thiếu** (`Exhibit D`) — nếu đưa vào sử dụng ngay sẽ có nguy cơ phân loại sai hoặc trích xuất sai dữ liệu tín dụng.
  * **Rào cản phê duyệt bảo mật trong 8 tuần:** `Section 6` và `Section 7` khẳng định rõ mọi tích hợp Production AI mới đều cần phê duyệt bảo mật và tuân thủ từ ban lãnh đạo mà **không đảm bảo hoàn tất trong 8 tuần**. Trong khi đó, thiết kế **Slot-Based Upload** (khách tải file vào đúng khe nào thì hệ thống gắn nhãn theo khe đó) đã giải quyết được bài toán phân loại tài liệu ngay từ gốc với rủi ro bằng 0.

---

### PART 4.2: MEASURABLE SUCCESS INDICATORS & PRE-PILOT RELEASE CONDITION

#### 1. Two Measurable Success Indicators (KPIs)

| Measurable Success Indicator (KPI) | Current Baseline (Facts) | Proposed Pilot Target (Mục tiêu đề xuất) | Evaluation Period & Measurement Method |
| :--- | :---: | :---: | :--- |
| **1. Tỷ lệ hồ sơ trong Pilot phải yêu cầu bổ sung (Missing-Document Follow-up Rate)**<br>*(Đo lường hiệu quả chặn lỗi tại nguồn của PBI #1, #2, #3)* | • Toàn bộ đơn: **65%** (780/1.200 đơn/tháng – `Exhibit A`).<br>• SME vay lần đầu: **75%** (600/800 đơn – `Exhibit B`).<br>• SME vay lại: **45%** (180/400 đơn – `Exhibit B`). | • Toàn bộ đơn trong Pilot: **$\le$ 35–40%**.<br>• SME vay lần đầu: **$\le$ 45%**.<br>• *Chỉ số bảo vệ (Guardrail):* Tỷ lệ hoàn tất nộp đơn trên Mobile không giảm so với trước Pilot. | **Đo trong 4 tuần đầu tiên của Controlled Pilot** (hoặc trên 300 hồ sơ Pilot đầu tiên), so sánh trực tiếp với nhóm hồ sơ đối chứng ngoài Pilot cùng kỳ. *(Theo dõi bổ trợ xem median duration tới khi xong Initial Review của nhóm Pilot có dịch chuyển từ **7 ngày làm việc** hướng về mốc **$\le$ 5 ngày** hay không – `Exhibit A`).* |
| **2. Thời gian nhân viên xử lý trung bình mỗi ca bổ sung & Tỷ lệ khách sửa xong trong 1 ngày làm việc**<br>*(Đo lường hiệu quả của PBI #4 – One-Click Surgical Fix-Loop)* | • Thời gian nhân viên xử lý: **10 phút/ca follow-up** (tương đương **130 giờ công/tháng** – `Exhibit A`).<br>• Tỷ lệ đơn lỗi được khách sửa trong 1 ngày làm việc: **68%** (`Exhibit A`). | • Thời gian nhân viên xử lý mỗi ca bổ sung giảm xuống **$\le$ 5–6 phút/ca** *(tiết kiệm $\ge$ 40% thời gian mỗi ca)*.<br>• Tỷ lệ đơn lỗi được khách sửa xong trong 1 ngày làm việc tăng từ **68% lên $\ge$ 80%**. | **Tổng kết vào cuối tuần thứ 4 của Controlled Pilot**, đo bằng thời gian trung bình từ lúc nhân viên tick chọn mã lý do lỗi trên khe tài liệu + kiểm tra lại file nộp bù so với quy trình gọi điện/gửi email thủ công hiện tại. |

#### 2. One Critical Test / Release Condition Before Controlled Pilot (`Section 6`)
Tuân thủ yêu cầu bắt buộc tại `Section 6` (*"A security review and critical functionality testing must be completed before the pilot"*), giải pháp **SmartPack** chỉ được phép phát hành ra **Controlled Pilot** sau Sprint 4 khi vượt qua **Cổng Kiểm định Kép (Pre-Pilot Release Gate)** sau:
* **Mandatory Security Review & Mobile E2E Critical Path Testing (100% Pass & Zero Critical/High Defects):**
  1. **Security & Access Control Verification:** Bộ phận Bảo mật xác nhận 100% tài liệu tải lên theo từng khe (Slot) và cơ chế *Deep-link* trong *Transactional email* bổ sung hồ sơ được lưu trữ cố định trong **Document storage** được phê duyệt (`Section 5`, `Section 6`); bắt buộc yêu cầu phiên đăng nhập xác thực (authenticated session) mới được xem hoặc thay thế tài liệu, đảm bảo **0 lỗ hổng rò rỉ dữ liệu chéo** giữa các tài khoản doanh nghiệp SME.
  2. **Critical Functionality Testing trên Mobile:** QA Engineer xác nhận **100% Pass Rate (0 lỗi Critical/High)** cho luồng kiểm thử End-to-End trên các thiết bị di động phổ biến (đáp ứng 78% lưu lượng Mobile – `Exhibit A`): *Trả lời 4 câu hỏi Wizard sinh đúng 100% Checklist theo quy định nội bộ $\rightarrow$ Tải file PDF/JPG/PNG $\le 10\text{MB}$ vào từng Slot kèm kiểm tra cảnh báo ảnh mờ $\rightarrow$ Chặn nộp mềm khi thiếu Slot bắt buộc $\rightarrow$ Ops kích hoạt email bổ sung 1 chạm và khách hàng tải lại đúng khe lỗi*.
