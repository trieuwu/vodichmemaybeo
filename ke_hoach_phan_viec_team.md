# 📋 KẾ HOẠCH TÁC CHIẾN & PHÂN VIỆC TEAM FULL-STACK (19:47 – 21:00)

> **Lợi thế của Team:** Cả 4 anh em (**Triệu, Tú Anh, Đăng, Khải**) đều có tư duy **Full-stack (cân được cả 5 role PM, PO, BA, Dev, QA)**. Vì vậy, thay vì chia việc kiểu "ai biết phần nấy", chúng ta sẽ chia theo mô hình **4 Mũi Nhọn Song Song + Đọc Chéo (Cross-Review)** để không ai phải chờ ai, tốc độ viết nhanh gấp 4 lần mà văn phong vẫn thống nhất như một người viết.

---

## 1. Bảng Phân Công Nhiệm Vụ Chính & Vai Trò Hỗ Trợ (Cross-Role Matrix)

| Thành viên | Role Chính | Phần Bài Thi Đảm Nhận (Owner) | Role Phụ / Hỗ Trợ Chéo (Full-stack Backup) | Quota Số Trang |
| :--- | :--- | :--- | :--- | :--- |
| **Triệu** | **PM / PO** *(Kiêm BA chiến lược)* | **Phần 1** (Problem Identification & Product Goal)<br>**Phần 4 - Mục 1** (Quyết định của PO trước 2 biến cố ở Sprint 2 Review) | • Chốt "Xương sống" số liệu cho cả team.<br>• Kiểm soát tổng thể mạch logic & ép file chuẩn **$\le$ 6 trang**. | **~1.2 trang** *(Phần 1: 0.7 trang, Phần 4.1: 0.5 trang)* |
| **Tú Anh** | **BA** *(Kiêm UX/Product Designer)* | **Phần 2** (Creative Service Redesign: Mô tả giải pháp, Bảng luồng Before vs. After, Giải quyết nguyên nhân gốc rễ) | • Vẽ nhanh 1 bảng Wireframe / Sơ đồ luồng trực quan.<br>• Phối hợp với **Đăng** để 4 Backlog Items ở Phần 3 khớp 100% với tính năng ở Phần 2. | **~1.5 trang** |
| **Đăng** | **DEV** *(Kiêm Scrum Master / System Architect)* | **Phần 3 - Mục A, B, D** (4 Product Backlog Items, Lộ trình 4 Sprints Incremental Delivery, Rủi ro & Tính năng Defer sau MVP) | • Đảm bảo kiến trúc tận dụng hạ tầng có sẵn (Section 5) và khớp năng lực team (2 Dev, 1 BA, 0.5 QA).<br>• Chốt sớm PBI số 1 ở phút thứ 10 để **Khải** viết Acceptance Criteria. | **~1.8 trang** *(Dùng bảng biểu gọn)* |
| **Khải** | **Tester / QA** *(Kiêm Data & Compliance Analyst)* | **Phần 3 - Mục C** (Acceptance Criteria cho PBI #1 + Definition of Done)<br>**Phần 4 - Mục 2** (2 chỉ số KPI đo lường Pilot + 1 Critical Release Condition) | • Thiết lập file Word/Docs chuẩn format ngay từ đầu.<br>• "Gác đền" rà soát toàn bộ trích dẫn (`Exhibit A–D`, `Section 5–7`) và điều kiện bắt buộc của đề bài. | **~1.2 trang** *(Phần 3.C: 0.5 trang, Phần 4.2: 0.7 trang)* |

---

## 2. Cơ Chế Phối Hợp "Bắt Tay" (Hand-off) Để Không Bị Lệch Pha

Vì 4 người viết cùng lúc trên 1 file, chỉ cần **3 điểm chạm (Sync Points)** cực ngắn sau đây để bài viết khớp tuyệt đối:

| Điểm chạm | Người phối hợp | Nội dung khớp nối (Chỉ mất 1-2 phút trao đổi) |
| :--- | :--- | :--- |
| **Bắt tay 1 (19:55)** | **Triệu (PO) ↔ Tú Anh (BA)** | **Triệu** chốt *Product Goal* (VD: Giảm tỷ lệ hồ sơ bị follow-up từ 65% xuống $\le 30\%$) $\rightarrow$ **Tú Anh** bám đúng con số và nguyên nhân gốc rễ đó để vẽ luồng *Redesigned Workflow* ở Phần 2. |
| **Bắt tay 2 (20:00)** | **Tú Anh (BA) ↔ Đăng (Dev)** | **Tú Anh** đọc tên 3-4 tính năng chính trong giải pháp ở Phần 2 $\rightarrow$ **Đăng** biến ngay 4 tính năng đó thành **4 Product Backlog Items (PBI #1 $\rightarrow$ #4)** ở Phần 3.A. |
| **Bắt tay 3 (20:05)** | **Đăng (Dev) ↔ Khải (QA)** | **Đăng** chốt xong tên PBI #1 (Ưu tiên cao nhất) & Rủi ro kỹ thuật $\rightarrow$ **Khải** viết ngay *Acceptance Criteria (Given-When-Then)* cho PBI #1, *DoD* và *Critical Test Condition* trước khi chạy Pilot. |

---

## 3. Timeline Chi Tiết Từng Phút (19:47 – 21:00 | 73 Phút)

### ⏱️ Chặng 1: Chốt Gốc & Dựng Khung (19:47 – 19:55 | 8 Phút)

| Thời gian | Triệu (PM/PO) | Tú Anh (BA) | Đăng (DEV) | Khải (QA/Tester) |
| :--- | :--- | :--- | :--- | :--- |
| **19:47 – 19:55** | Chủ trì chốt nhanh trong 5 phút:<br>1. **Vấn đề chọn:** 65% hồ sơ (780/1.200) nộp thiếu/sai tài liệu phải follow-up.<br>2. **Giải pháp:** *Smart Dynamic Checklist & Pre-Submission Quality Check* (Web/Mobile) + *AI Prototype ở chế độ hỗ trợ nhân viên nội bộ*. | Liệt kê nhanh 3 điểm khác biệt lớn nhất giữa quy trình cũ (5 bước) và quy trình mới để chuẩn bị kẻ bảng Before/After. | Phác thảo nhanh tên 4 Product Backlog Items (PBI 1 $\rightarrow$ 4) và phân bổ vào 4 Sprints (8 tuần). | Tạo ngay file Google Docs chung, cài sẵn format chuẩn:<br>• Khổ **A4**, Lề **2 cm**<br>• Font **Times New Roman 12pt**, giãn dòng **1.5**<br>• Bảng biểu: **10.5pt**, giãn dòng **1.0**<br>• Đặt sẵn 4 Heading lớn. |

---

### ⏱️ Chặng 2: Tăng Tốc Viết Song Song - Deep Work (19:55 – 20:30 | 35 Phút)

| Thời gian | Triệu (PM/PO) | Tú Anh (BA) | Đăng (DEV) | Khải (QA/Tester) |
| :--- | :--- | :--- | :--- | :--- |
| **19:55 – 20:12** *(17 phút)* | **Viết Phần 1:**<br>• Nêu rõ đối tượng bị ảnh hưởng: SME vay lần đầu (75% bị thiếu hồ sơ - *Exhibit B*) & nhân viên RM/Credit Ops.<br>• Đưa 3 bằng chứng số liệu từ *Exhibit A, B, D*.<br>• Viết **1 Product Goal** + **1 Assumption** cần kiểm chứng. | **Viết Phần 2 (Mục 1 & 2):**<br>• Mô tả giải pháp và giá trị cho SME & Ngân hàng.<br>• Kẻ bảng **Redesigned Workflow (Current vs. Redesigned)** làm nổi bật cách chặn lỗi thiếu hồ sơ ngay từ bước chuẩn bị & upload trên Mobile (78% user). | **Viết Phần 3 - Mục A & B:**<br>• Lập bảng **4 PBIs** (Mô tả, Customer/Business Value, Priority 1–4).<br>• Lập bảng **Incremental Delivery (Sprint 1 $\rightarrow$ 4)**: Nêu rõ *Sprint Goal* của Sprint 1 và *Forecast Objectives* cho Sprint 2–4, khớp với 2 Dev, 1 BA, 0.5 QA. | **Viết Phần 3 - Mục C:**<br>• Viết **1 Acceptance Criterion** cụ thể, kiểm thử được cho PBI #1 của Đăng.<br>• Viết **4 điều kiện Definition of Done (DoD)** (Code & Unit Test, QA Test với 50% capacity, Security & Access Control theo *Section 6*, PO nghiệm thu). |
| **20:12 – 20:30** *(18 phút)* | **Viết Phần 4 - Mục 1:**<br>• **Phản hồi Diễn biến 1** (5/8 user lúng túng bước tiếp theo): Ưu tiên đưa việc cải thiện UX/điều hướng vào ngay Sprint 3 và kiểm thử lại.<br>• **Phản hồi Diễn biến 2** (Sếp đòi thêm AI Assistant): Từ chối đưa vào MVP (Defer sang Post-MVP) để bảo vệ Product Goal, vì vướng rào cản phê duyệt AI trong 2 Sprint cuối (*Section 6*) & cố định capacity. | **Viết Phần 2 (Mục 3) & Visual:**<br>• Giải thích cách giải pháp xử lý tận gốc nguyên nhân (tài liệu phức tạp theo từng khoản vay & 41% ảnh chụp bị mờ/sai).<br>• Tạo nhanh **1 khung Wireframe / Mockup dạng bảng trực quan** minh họa màn hình *Dynamic Checklist & Cảnh báo ảnh mờ* trên Mobile. | **Viết Phần 3 - Mục D (Feasibility & Scope):**<br>• Lập bảng **3 Rủi ro/Phụ thuộc** xếp theo độ quan trọng (1. Nghẽn cổ chai QA 50% & Ops chỉ có 2h/tuần; 2. 41% tài liệu là ảnh chụp chất lượng thấp; 3. Phê duyệt bảo mật).<br>• Nêu cách xử lý rủi ro số 1.<br>• Nêu **1 tính năng Defer sau MVP** (AI tự động phân loại/duyệt 100% không cần người). | **Viết Phần 4 - Mục 2:**<br>• Lập bảng **2 Success Indicators (KPIs)** có Target & Thời gian đo rõ ràng (VD: Tỷ lệ follow-up giảm từ 65% xuống $\le 30\%$ trong 4 tuần Pilot; Thời gian review trung vị giảm từ 7 xuống $\le 5$ ngày).<br>• Nêu **1 Critical Test / Release Condition** trước Pilot (Security Review + E2E Critical Path Test trên Mobile theo *Section 6*). |

---

### ⏱️ Chặng 3: Đọc Chéo Full-Stack & Ép Trang (20:30 – 20:50 | 20 Phút)

> **Nguyên tắc Full-stack:** Người này sẽ dùng chuyên môn phụ của mình để review phần của người kia, đảm bảo không sót bất kỳ câu hỏi nhỏ nào trong đề bài.

| Thời gian | Triệu (Review Phần 2 & Tổng thể) | Tú Anh (Review Phần 1 & 4.1) | Đăng (Review Phần 3.C & 4.2) | Khải (Review Phần 3.A, B, D) |
| :--- | :--- | :--- | :--- | :--- |
| **20:30 – 20:40** *(10 phút)* | Kiểm tra Phần 2 của **Tú Anh** xem đã bám sát Product Goal chưa, các bảng biểu có đọc rõ ở mức **100% zoom** không. | Kiểm tra Phần 1 & 4.1 của **Triệu** xem lập luận từ chối AI Assistant của stakeholder đã khéo léo, đúng tinh thần Scrum và dẫn chứng *Section 6* chưa. | Kiểm tra DoD, Acceptance Criteria và KPI của **Khải** xem đã cụ thể, có con số đo lường (measurable) và khớp với kiến trúc kỹ thuật chưa. | Đối chiếu toàn bộ Phần 3 của **Đăng** với đề bài: Đã đủ 4 PBIs chưa? Đã tính đến ràng buộc 2h/tuần của nhân viên Ops và 50% QA chưa? |
| **20:40 – 20:50** *(10 phút)* | **Căn chỉnh & Cắt gọt trang:** Cả 4 anh em cùng nhìn tổng thể file. Nếu bài đang dài 6.5 trang, tiến hành gộp các đoạn văn dài thành gạch đầu dòng hoặc bảng biểu để gói gọn đẹp trong **5.5 – 6.0 trang** (tuyệt đối không để rớt dòng sang trang 7). | Hỗ trợ rút gọn câu chữ ở Phần 2 nếu bị tràn trang; đảm bảo tên gọi của giải pháp thống nhất từ trang 1 đến trang 6. | Kiểm tra lại định dạng tất cả các bảng (Font 10–11pt, Single spacing, không bị cắt bảng vô duyên giữa 2 trang). | Kiểm tra Checklist nộp bài lần cuối:<br>✅ Có trích dẫn inline (`Exhibit A`, `Section 6`...)<br>✅ Không có Phụ lục (Appendices)<br>✅ Đủ 4 Phần theo đúng thứ tự. |

---

### ⏱️ Chặng 4: Xuất File & Nộp Bài An Toàn (20:50 – 21:00 | 10 Phút)

| Thời gian | Người chịu trách nhiệm | Hành động cụ thể |
| :--- | :--- | :--- |
| **20:50 – 20:53** | **Triệu (PM/PO)** | Tải file từ Google Docs xuống định dạng `.docx`, đặt tên chính xác theo quy định: `Team Name_Round 1.docx`. |
| **20:53 – 20:55** | **Khải (QA) & Đăng (Dev)** | Mở file `.docx` trực tiếp trên Microsoft Word để kiểm tra: Dung lượng **< 5 MB**, số trang **$\le$ 6 trang** (vì đôi khi từ Google Docs tải về Word bị nhảy dòng sang trang 7). |
| **20:55 – 21:00** | **Triệu (PM/PO)** *(Tú Anh dự phòng)* | Upload file lên hệ thống thi trước 5 phút so với hạn chót để tránh nghẽn mạng. Chụp màn hình xác nhận đã nộp thành công. |
