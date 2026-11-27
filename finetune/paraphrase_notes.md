# Khung Trình Bày & Tư Liệu Paraphrase Nộp Bài (Finetune & Presentation Plan)

> **Mục đích:** Đây là khung sườn trình bày chuẩn theo đúng bố cục file `.docx` (tối đa **6 trang A4**) kèm tư liệu cốt lõi đã chắt lọc súc tích. Anh em dùng cấu trúc này để gõ dần (type) và paraphrase theo văn phong tự nhiên trước khi xuất file nộp.

---

## 📐 I. KẾ HOẠCH TRÌNH BÀY & PHÂN BỔ SỐ TRANG (6-PAGE LAYOUT PLAN)

* **Chuẩn Format bắt buộc:** Khổ A4 | Lề 2–2.5 cm | Văn bản: Times New Roman 12pt, giãn dòng 1.5 | Bảng biểu: Times New Roman 10–11pt, giãn dòng 1.0 (Single), đọc rõ ở 100% zoom | Không dùng Phụ lục (Appendices).
* **Nguyên tắc viết súc tích:** Tối đa 2–3 câu cho mỗi đoạn văn; ưu tiên tuyệt đối dùng **Bảng biểu (Compact Tables)** và **Bullet points** có in đậm từ khóa đầu dòng.

| Phần (Section) | Cấu trúc Trình bày trong File `.docx` | Định mức Trang | Người phụ trách |
| :--- | :--- | :---: | :--- |
| **Header** | Tên đội + Tiêu đề Proposal (2 dòng đầu trang 1, không làm trang bìa riêng để tiết kiệm giấy). | **0.1 trang** | Triệu |
| **Part 1: Problem Identification & Product Goal** | • **1.1. Affected Users & Selected Problem:** 1 bảng nhỏ hoặc 2 gạch đầu dòng.<br>• **1.2. Supporting Evidence:** 3 gạch đầu dòng trích dẫn số liệu (`Exhibit A, B, D`).<br>• **1.3. Product Goal & Key Assumption:** 2 khung quote/bullet ngắn gọn. | **0.9 trang** *(Hết Trang 1)* | Triệu |
| **Part 2: Creative Service Redesign** | • **2.1. Proposed Solution & Value:** 3 gạch đầu dòng (3 trụ cột tính năng) + 2 dòng Value (Customer vs. Bank).<br>• **2.2. Redesigned Workflow:** 1 Bảng so sánh *Current vs. Redesigned* + 1 khung Wireframe/Flow dạng bảng gọn.<br>• **2.3. Addressing Root Cause:** 2 gạch đầu dòng giải thích cách chặn lỗi từ nguồn & lý do không phụ thuộc AI Prototype. | **1.5 trang** *(Trang 2 – giữa Trang 3)* | Tú Anh |
| **Part 3: Scrum-Based MVP Planning & Execution** | • **3.A. Product Backlog:** 1 Bảng gồm 4 PBIs + 1 dòng *Acceptance Criterion (Given-When-Then)* ngay dưới bảng.<br>• **3.B. Incremental Delivery:** 1 Bảng 4 dòng ứng với 4 Sprints (Goal/Forecast, Increment, Capacity).<br>• **3.C. Definition of Done:** 4 gạch đầu dòng ngắn gọn.<br>• **3.D. Feasibility & Scope:** 1 Bảng 3 Rủi ro (kèm Mitigation cho Risk #1) + 1 đoạn ngắn nêu tính năng Defer sau MVP. | **2.2 trang** *(Giữa Trang 3 – cuối Trang 5)* | Đăng & Khải |
| **Part 4: Inspection, Adaptation & Validation** | • **4.1. PO Response to Sprint 2 Review:** 1 Bảng 2 dòng (Development 1 & Development 2: Quyết định của PO, Bảo vệ Product Goal, Kế hoạch S3–S4).<br>• **4.2. Validation & Pre-Pilot Gate:** 1 Bảng 2 KPIs (Baseline, Target, Period) + 1 gạch đầu dòng cho *Critical Release Condition*. | **1.3 trang** *(Cuối Trang 5 – hết Trang 6)* | Triệu & Khải |

---

## ✍️ II. KHUNG NỘI DUNG SÚC TÍCH ĐỂ TYPE DẦN & PARAPHRASE

### PART 1: PROBLEM IDENTIFICATION & PRODUCT GOAL (~0.9 Trang)

#### 1.1. Affected Users & Selected Problem
* **Affected Users:**
  * *Primary & Returning SME Owners:* Gặp khó khăn trong việc xác định đúng danh mục giấy tờ theo từng gói vay và chuẩn bị tài liệu đạt chuẩn trên thiết bị di động (Section 2, 3).
  * *Bank Operations (RM, Customer Support, Credit Ops):* Mất nhiều thời gian rà soát lỗi, liên hệ đòi hồ sơ bổ sung (follow-up) và kiểm tra lại (Section 2, 3).
* **Selected Problem (Stages 1–3):** Tỷ lệ hồ sơ đăng ký tín dụng SME nộp thiếu, phân loại sai danh mục hoặc hình ảnh không đọc được ở mức rất cao, gây ra vòng lặp follow-up tốn kém và kéo dài gấp đôi thời gian xử lý.

#### 1.2. Supporting Evidence (Inline Citations)
* **Quy mô lỗi lớn nhất toàn hành trình (Exhibit A, B):** **65% tổng số đơn (780/1.200 đơn/tháng)** bị thiếu tài liệu phải follow-up. Nhóm khách vay lần đầu (chiếm 800/1.200 đơn) có tỷ lệ thiếu hồ sơ lên tới **75% (600 đơn)**; ngay cả khách vay lại cũng có tới **45% (180/400 đơn)** mắc lỗi.
* **Kéo dài gấp đôi thời gian xử lý & Lãng phí nguồn lực (Exhibit A):** Hồ sơ phải follow-up mất trung vị **8 ngày làm việc** để hoàn tất thẩm định sơ bộ, gấp đôi so với **4 ngày làm việc** của hồ sơ nộp đủ ngay từ đầu (kéo trung vị toàn ngân hàng lên 7 ngày). Nhân viên tốn **130 giờ công/tháng** ($780 \text{ đơn} \times 10 \text{ phút}$) chỉ để liên hệ và kiểm tra lại hồ sơ bổ sung, lớn hơn nhiều so với thời gian trả lời trạng thái (33.3 giờ - Exhibit C) hay nhập liệu thủ công (84 giờ - Exhibit D).
* **Đặc thù hành vi Mobile & Ảnh chụp chưa được kiểm soát (Exhibit A, D, Section 5):** **78%** đơn khởi tạo trên Mobile và **41%** tài liệu là ảnh chụp/scan, nhưng *Basic Validation* hiện tại chỉ kiểm tra định dạng (PDF/JPG/PNG) và dung lượng ($\le 10\text{MB}$) chứ chưa kiểm tra tính đầy đủ hay chất lượng ảnh.

#### 1.3. Product Goal & Key Assumption to Validate
* **Product Goal:** Trong 8 tuần (4 Sprints), chuyển giao giải pháp hướng dẫn hồ sơ động và cổng kiểm tra chất lượng trước khi nộp trên Portal/Mobile cho đợt Controlled Pilot, nhằm giảm tỷ lệ hồ sơ phải follow-up từ **65% xuống $\le$ 30%** và rút ngắn thời gian thẩm định sơ bộ trung vị từ **7 ngày xuống $\le$ 4.5 ngày làm việc**.
* **Key Assumption Requiring Validation:** Chủ doanh nghiệp SME (đặc biệt là 78% người dùng Mobile) sẵn sàng trả lời 3–4 câu hỏi phân loại đầu vào và đồng ý chụp/tải lại tài liệu ngay khi nhận cảnh báo thiếu file hoặc ảnh mờ trước khi bấm Submit, thay vì bỏ dở đơn đăng ký.

---

### PART 2: CREATIVE SERVICE REDESIGN (~1.5 Trang)

#### 2.1. Proposed Solution & Value Created
Nâng cấp nhẹ (lightweight upgrade) trực tiếp trên **Online Application Portal**, **Document Storage** và **Transactional Email** sẵn có (Section 5) thông qua 3 tính năng liên hoàn:
1. **Dynamic Requirement Wizard:** Hỏi 3–4 tiêu chí đầu vào (Sản phẩm vay, Loại hình SME, Khách mới/cũ) để tự động ánh xạ quy định nội bộ thành **Checklist tài liệu cá nhân hóa**.
2. **Slot-Based Upload & Pre-Submission Gate:** Chia giao diện tải file thành từng ô (Slot) bắt buộc kèm ảnh mẫu trực quan. Hệ thống tự động gắn nhãn danh mục theo từng Slot, kiểm tra nhanh độ mờ/độ phân giải ảnh chụp ngay trên trình duyệt Mobile và khóa nút **Submit** nếu còn trống ô bắt buộc.
3. **One-Click Resubmission Link:** Nếu nhân viên Ops cần yêu cầu bổ sung, chỉ cần tích chọn đúng Slot bị lỗi $\rightarrow$ Hệ thống gửi *Transactional Email* chứa link mở thẳng vào đúng ô tài liệu đó trên Mobile để khách tải lại và đồng bộ trạng thái tức thì.
* **Customer & Employee Value:** SME biết chính xác cần nộp gì, nộp đúng ngay lần đầu trên điện thoại và giảm thời gian chờ từ 8 xuống ~4 ngày; Ngân hàng tiết kiệm >50% trong số 130 giờ công follow-up/tháng và nhận bộ hồ sơ đã được phân loại sẵn.

#### 2.2. Redesigned Workflow (Current vs. Redesigned)

| Stage | Current Workflow (Section 2, 5) | Redesigned Workflow |
| :--- | :--- | :--- |
| **1. Discover requirements** | SME tự đọc quy định tĩnh trên web hoặc hỏi chi nhánh; dễ xác định sai giấy tờ cần nộp. | SME chọn 3–4 tiêu chí trên Mobile/Web $\rightarrow$ Hệ thống tự động sinh **Checklist cá nhân hóa** kèm hình mẫu chuẩn và lưu vào bản nháp (Draft). |
| **2. Prepare & upload** | Tải rời rạc nhiều file (41% ảnh chụp/scan); chỉ check file $\le 10\text{MB}$ nên thường bị thiếu, mờ hoặc sai danh mục. | **Tải file vào từng Slot bắt buộc** (tự động gắn đúng nhãn danh mục). Bộ lọc Client-side cảnh báo ảnh mờ & chặn Submit nếu thiếu ô bắt buộc. |
| **3. Completeness check & Status** | Nhân viên rà soát thủ công; 65% đơn phải liên hệ đòi bổ sung (10 phút/đơn); trạng thái xuất 1 lần/ngày. | Hồ sơ vào hệ thống đã đủ số lượng và phân loại chuẩn theo Slot. Nếu có file lỗi, nhân viên bắn **One-Click Resubmission Email** trong 1 chạm. |

#### 2.3. Addressing the Underlying Problem
* **Chuyển kiểm soát từ Reactive sang Proactive:** Đưa bước kiểm tra tính đầy đủ từ *sau khi nộp (bởi nhân viên ở Stage 3)* lên *trước khi nộp (tự động ở Stage 1–2)*, cắt đứt nguyên nhân gây ra 780 ca follow-up/tháng.
* **Giải quyết phân loại & chất lượng ảnh mà không mạo hiểm với AI Prototype:** Cơ chế *Slot-Based Upload* đảm bảo tài liệu được phân loại đúng 100% theo ngăn chứa mà không cần đưa bản *AI Classification Prototype* (chưa được kiểm chứng trên 41% ảnh chụp thực tế/file lỗi và không đảm bảo kịp phê duyệt bảo mật trong 8 tuần - Exhibit D, Section 6) lên môi trường khách hàng.

---

### PART 3: SCRUM-BASED MVP PLANNING & EXECUTION (~2.2 Trang)

#### 3.A. Product Backlog (4 Prioritized Items)

| Priority | Product Backlog Item (PBI) | Mô tả ngắn gọn | Giá trị mang lại (Customer & Business Value) |
| :---: | :--- | :--- | :--- |
| **1 (Highest)** | **Dynamic Checklist Engine** | Bộ hỏi đáp 3–4 tiêu chí ánh xạ quy định nội bộ thành danh sách tài liệu bắt buộc theo từng hồ sơ SME. | Xóa bỏ sự mơ hồ về thủ tục cho 75% khách vay lần đầu và 45% khách vay lại (Exhibit B). |
| **2** | **Slot-Based Upload & Completeness Gate** | Giao diện tải file theo từng ô bắt buộc (tự động gắn nhãn vào Document Storage) và chặn nộp đơn khi thiếu file. | Ngăn chặn trực tiếp 65% đơn nộp thiếu và triệt tiêu lỗi phân loại sai danh mục (Exhibit A). |
| **3** | **Mobile Image Quality & Visual Guide** | Hình mẫu giấy tờ trực quan kèm công cụ kiểm tra độ phân giải/độ mờ ảnh chụp (PDF/JPG/PNG $\le 10\text{MB}$) trên trình duyệt. | Tối ưu cho 78% người dùng Mobile và kiểm soát chất lượng 41% tài liệu ảnh chụp/scan (Exhibit A, D). |
| **4** | **One-Click Resubmission & Email Trigger** | Công cụ cho phép nhân viên Ops đánh dấu Slot lỗi để gửi Transactional Email kèm link tải lại và cập nhật trạng thái. | Giảm thời gian xử lý mỗi ca follow-up từ 10 phút xuống $<3$ phút; giảm 26% lượt hỏi trạng thái lặp lại (Exhibit A, C). |

* **Testable Acceptance Criterion cho PBI #1:**
  > **Given** khách hàng SME đăng ký lần đầu đã đăng nhập vào Online Portal trên Mobile, **When** khách hàng chọn gói *"Vay vốn lưu động"*, loại hình *"Công ty TNHH"* và bấm xác nhận, **Then** hệ thống hiển thị chính xác danh sách các tài liệu bắt buộc tương ứng trong $<2$ giây, ẩn các giấy tờ không liên quan và lưu cấu hình vào bản nháp (Draft).

#### 3.B. Incremental Delivery (4 Sprints / 8 Weeks)

| Sprint | Sprint Goal (S1) / Forecast Objectives (S2–S4) | Usable Increment Demonstrated | Phân bổ Capacity (2 Dev, 1 BA, 0.5 QA, 2h/wk Ops) |
| :--- | :--- | :--- | :--- |
| **Sprint 1**<br>*(W1–2)* | **Sprint Goal:** Chuẩn hóa ma trận quy định hồ sơ và ra mắt bộ sinh Checklist động (PBI #1) trên Web/Mobile. | SME chọn tiêu chí vay trên Staging $\rightarrow$ Hệ thống xuất đúng danh mục giấy tờ bắt buộc và lưu được bản nháp. | **BA/PO** soạn trước bảng rule để chỉ dùng **2h/tuần** của nhân viên Ops cho việc xác nhận; **2 Dev** code rule-engine; **QA (5 ngày)** test bộ rule. |
| **Sprint 2**<br>*(W3–4)* | **Forecast:** Hoàn thiện giao diện tải file theo Slot và cổng chặn nộp thiếu (PBI #2) kết nối Document Storage. | SME tải file vào từng Slot, hệ thống tự động gắn nhãn danh mục và khóa nút Submit nếu còn ô bắt buộc bị trống. | Tái sử dụng Portal & Storage (Section 5); cuối Sprint chạy Usability Evaluation với 8 users và demo tại Sprint Review. |
| **Sprint 3**<br>*(W5–6)* | **Forecast:** Cải thiện điều hướng UX từ phản hồi Sprint 2 và tích hợp kiểm tra chất lượng ảnh chụp trên Mobile (PBI #3). | Luồng điều hướng bước tiếp theo rõ ràng; hệ thống tự động cảnh báo khi khách hàng tải ảnh chụp bị mờ/sai chuẩn trên Mobile. | **2 Dev** sửa UX & code bộ lọc ảnh client-side; **QA (5 ngày)** tập trung test tương thích trên các thiết bị di động (78% traffic). |
| **Sprint 4**<br>*(W7–8)* | **Forecast:** Hoàn thiện luồng yêu cầu bổ sung 1 chạm (PBI #4), vượt qua Security Review và sẵn sàng cho Pilot. | Luồng End-to-End hoàn chỉnh từ lúc SME nộp đơn đến khi nhân viên Ops kiểm tra và gửi link bổ sung qua Transactional Email. | Dành trọng tâm cho **Security Review & Critical Functionality Testing** (yêu cầu bắt buộc trước Pilot theo Section 6). |

#### 3.C. Definition of Done (DoD)
1. **Functional & Mobile Compatibility:** Code đã được peer-review, vượt qua Unit Test và 100% Acceptance Criteria trên cả trình duyệt Web và Mobile (đáp ứng 78% traffic di động - Exhibit A).
2. **Security & Access Control (Section 6):** Tài liệu tải lên được lưu trữ hoàn toàn trong môi trường Document Storage được phê duyệt của Bank X, đảm bảo phân quyền truy cập hợp lệ.
3. **Quality Assurance within Capacity:** Đã được QA Engineer kiểm thử tích hợp (trong định mức 5 ngày/Sprint) với **0 lỗi Critical/High-severity**.
4. **Business Sign-off:** Được Product Owner nghiệm thu và đối chiếu quy tắc nghiệp vụ cùng đại diện Bank Operations (trong khung 2 giờ/tuần).

#### 3.D. Feasibility and Scope
* **Key Risks / Dependencies (Xếp theo độ quan trọng giảm dần):**
  1. **[Risk #1 - Quan trọng nhất] Nút thắt thời gian của Nhân viên Ops (2h/tuần) và QA (50% ~ 5 ngày/Sprint - Section 6):**
     * *Mitigation:* BA chuẩn bị sẵn ma trận tài liệu từ văn bản nội bộ để 2h/tuần của Ops chỉ dùng cho việc sign-off và usability test. Dev áp dụng bàn giao cuốn chiếu từ giữa Sprint và viết Unit Test tự động để QA rải đều khối lượng test trong 5 ngày.
  2. **[Risk #2] Chất lượng 41% ảnh chụp thực tế rất đa dạng (Exhibit D):** Bộ lọc độ mờ có thể cảnh báo nhầm (false positive). *Mitigation:* Thiết kế cảnh báo độ mờ ở dạng *Soft Warning* kèm ảnh mẫu đối chiếu để khách hàng vẫn có quyền xác nhận nộp nếu chữ vẫn đọc được.
  3. **[Risk #3] Yêu cầu hoàn tất Security Review trước Pilot (Section 6):** *Mitigation:* Tái sử dụng 100% hạ tầng xác thực, lưu trữ và email hiện có để thu hẹp phạm vi rà soát bảo mật.
* **Feature Deferred Beyond MVP:** Hoãn tính năng **AI Document Classification & OCR Auto-Transcription (chiếm 35% thời gian review - Exhibit D) trên môi trường Production**. *Lý do:* Bản AI prototype mới chỉ test trên 50 file kỹ thuật số sạch, chưa được kiểm chứng trên 41% ảnh chụp/scan thực tế (Exhibit D), và việc xin phê duyệt bảo mật/compliance cho AI không đảm bảo kịp trong 8 tuần (Section 6).

---

### PART 4: INSPECTION, ADAPTATION, AND VALIDATION (~1.3 Trang)

#### 4.1. Product Owner Response to Sprint 2 Review Developments (Section 7)

| Diễn biến (Development) | Quyết định của Product Owner | Bảo vệ Product Goal & Kế hoạch Sprint 3–4 |
| :--- | :--- | :--- |
| **Dev 1: 5/8 người dùng lúng túng không biết thao tác gì tiếp theo** *(Mẫu nhỏ nhưng chỉ ra rủi ro usability)* | **Thích nghi ngay (Adapt):** Đưa PBI *"Cải thiện điều hướng UI/UX (thanh tiến trình Step-by-Step, nút CTA nổi bật & micro-copy hướng dẫn)"* lên đầu **Sprint 3** và kiểm thử lại. | • **Bảo vệ Product Goal:** Nếu người dùng bị khựng lại không biết bước tiếp theo trên Mobile, họ sẽ bỏ dở hoặc nộp thiếu, làm thất bại mục tiêu giảm tỷ lệ follow-up xuống $\le 30\%$.<br>• **Sprint 3–4:** Dành 2–3 ngày đầu Sprint 3 để sửa UX và kiểm chứng lại trong buổi làm việc hàng tuần (2h/tuần) với Ops & nhóm user mới. |
| **Dev 2: Stakeholder cấp cao yêu cầu thêm AI Customer Assistant trước Pilot** *(Ngoài scope MVP, chưa chắc kịp duyệt AI)* | **Từ chối đưa vào MVP (Defer to Post-MVP):** PO dùng *Decision authority (Section 6)* giải thích bằng bằng chứng và dời tính năng này sang giai đoạn sau Pilot. | • **Bảo vệ Product Goal & Deadline:** Phê duyệt production cho tích hợp AI mới **không đảm bảo hoàn tất trong 2 Sprint cuối** (Section 6, 7); cố làm sẽ gây nguy cơ vỡ deadline Pilot và quá tải capacity cố định (2 Dev, 0.5 QA).<br>• **Giải pháp thay thế ở Sprint 3:** Bổ sung *Contextual FAQ/Tooltips tĩnh* ngay trong lúc sửa UX ở Dev 1 để hỗ trợ khách hàng mà không cần AI. |

#### 4.2. Measurable Success Indicators & Pre-Pilot Release Condition

| Measurable Success Indicator (KPI) | Current Baseline | Pilot Target | Evaluation Period |
| :--- | :---: | :---: | :--- |
| **1. Tỷ lệ hồ sơ phải follow-up do thiếu/lỗi tài liệu (Missing-Document Follow-up Rate)** | **65%** *(Khách mới: 75% - Exhibit A, B)* | **$\le$ 30%** *(Khách mới: $\le$ 35%)* | Trong **4 tuần đầu tiên** của Controlled Pilot (hoặc trên **300 hồ sơ SME đầu tiên** đi qua luồng mới). |
| **2. Thời gian trung vị hoàn tất thẩm định sơ bộ (Median Initial Document Review Duration)** | **7 ngày làm việc** *(Có follow-up: 8 ngày - Exhibit A)* | **$\le$ 4.5 ngày làm việc** | Tổng kết vào **cuối tuần thứ 4** của đợt Controlled Pilot. |

* **Critical Test / Release Condition Before Controlled Pilot (Section 6):**
  * **Security & Mobile E2E Critical Path Gate:** Trước khi mở Pilot sau Sprint 4, giải pháp bắt buộc phải: (1) Vượt qua **Security & Access Control Review** xác nhận 100% file tải qua các Slot và link *One-Click Resubmission* nằm trong Document Storage được phê duyệt, không rò rỉ dữ liệu chéo giữa các tài khoản SME; và (2) Đạt **100% Pass Rate (0 lỗi Critical/High)** cho luồng kiểm thử End-to-End trên thiết bị di động.
