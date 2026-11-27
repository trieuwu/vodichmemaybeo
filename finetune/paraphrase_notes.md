# Tư liệu & Ý tưởng Cốt lõi để Anh Em Paraphrase Khi Viết Bài (Finetune Notes)

> File này dùng làm nguyên liệu ý tưởng (bullet points, số liệu đối chiếu, góc nhìn lập luận) để **Triệu, Tú Anh, Đăng, Khải** tự diễn đạt (paraphrase) theo văn phong cá nhân trước khi đưa vào file Word cuối cùng.

---

## 1. Gợi ý Lập luận cho Part 1 (Problem & Product Goal - Triệu)
* **Góc nhìn chọn Vấn đề (Stage 1 - 3: Nộp thiếu & sai hồ sơ dẫn đến Follow-up):**
  * Đây là điểm nghẽn lớn nhất vì nó ảnh hưởng tới **65% tổng lượng đơn (780/1.200 đơn/tháng)** (Exhibit A), lớn hơn nhiều so với vấn đề hỏi trạng thái (400 lượt/tháng x 5 phút = 33.3 giờ - Exhibit C) hay nhập liệu thủ công (35% của 240 giờ = 84 giờ - Exhibit D).
  * Riêng việc xử lý follow-up đã ngốn `780 x 10 phút = 130 giờ công/tháng` và làm thời gian chờ của khách tăng gấp đôi từ `4 ngày` lên `8 ngày làm việc` (Exhibit A).
  * Nhóm khách hàng mới (First-time SMEs) chiếm 2/3 lượng đơn (`800/1.200`) và có tỷ lệ lỗi lên tới `75%` (Exhibit B) vì quy định hồ sơ thay đổi phức tạp theo từng khoản vay và loại hình doanh nghiệp (Section 2, 5).
* **Khung công thức viết Product Goal (để paraphrase):**
  * *[Hành động/Giải pháp]* + *[Đối tượng mục tiêu]* + *[Chỉ số cải thiện từ Baseline -> Target]* + *[Trong khung thời gian 8 tuần / Controlled Pilot]*.
* **Gợi ý Assumption cần kiểm chứng:**
  * Vì `78%` đơn khởi tạo trên điện thoại (Exhibit A), giả định sống còn là: Khách hàng SME sẵn sàng trả lời bộ câu hỏi lọc hồ sơ đầu vào và chịu chụp/tải lại giấy tờ ngay trên điện thoại khi hệ thống báo thiếu hoặc báo ảnh mờ, thay vì thấy phức tạp mà thoát ứng dụng.

---

## 2. Gợi ý Lập luận cho Part 2 (Service Redesign - Tú Anh)
* **Ý tưởng Giải pháp (Tận dụng tối đa hạ tầng Section 5, né bẫy phê duyệt AI Section 6):**
  * **Bước 1 - Dynamic Checklist Wizard:** Hỏi 3-4 câu đầu vào (Loại khoản vay, Loại hình SME, Vay lần đầu/Vay lại) -> Sinh ra đúng danh sách giấy tờ bắt buộc.
  * **Bước 2 - Slot-Based Upload & Pre-Submission Gate:** Thay vì 1 chỗ upload chung khiến khách nộp thiếu hoặc phân loại sai, tách thành từng "ô" (Slot) bắt buộc kèm ảnh mẫu minh họa. Nâng cấp *Basic Validation* hiện có để chặn nộp (hoặc cảnh báo rõ) khi chưa điền đủ các ô bắt buộc + kiểm tra nhanh độ mờ/độ phân giải ảnh chụp trên mobile (giải quyết `41%` file là ảnh chụp/scan - Exhibit D).
  * **Bước 3 - One-Click Resubmission qua Transactional Email:** Nếu nhân viên Credit Ops vẫn cần khách nộp lại 1 giấy tờ, bấm chọn giấy tờ đó -> Hệ thống bắn *Transactional Email* (đã có sẵn ở Section 5) chứa link mở thẳng vào đúng ô cần tải lại trên điện thoại, đồng thời cập nhật trạng thái ngay.
* **Điểm ăn điểm khi giải thích Root Cause:**
  * Việc chia từng ô tải file (Slot-based) giúp **tự động phân loại đúng danh mục 100%** ngay lúc khách tải lên mà không cần dùng đến bản *AI Document Classification Prototype* (vốn chưa được kiểm thử trên ảnh chụp mờ/lỗi thực tế và không chắc xin được phê duyệt bảo mật trong 8 tuần - Exhibit D, Section 6).

---

## 3. Gợi ý Lập luận cho Part 3 (Scrum MVP Plan - Đăng & Khải)
* **4 Product Backlog Items (PBI #1 -> #4):**
  1. *PBI 1:* Bộ quy tắc sinh Checklist tài liệu động theo hồ sơ SME (Dynamic Checklist Engine).
  2. *PBI 2:* Giao diện tải file theo từng Slot bắt buộc & cổng kiểm tra đủ số lượng trước khi Submit (Slot-Based Upload & Completeness Gate).
  3. *PBI 3:* Bộ kiểm tra chất lượng ảnh chụp trên Mobile & hình mẫu trực quan (Mobile Image Quality & Visual Guide).
  4. *PBI 4:* Tính năng yêu cầu bổ sung 1 chạm cho nhân viên Ops qua Transactional Email (One-Click Resubmission Trigger).
* **Lưu ý khi chia 4 Sprints (Incremental Delivery):**
  * Nhớ nhấn mạnh chỉ có **Sprint 1** là chốt **Sprint Goal** cứng, còn **Sprint 2, 3, 4** là **Forecast Objectives** sẽ được tinh chỉnh qua từng Sprint Review.
  * Phải nhắc đến cách xoay xở với **QA chỉ có 50% thời gian (5 ngày/Sprint)** và **Nhân viên Ops chỉ có 2 giờ/tuần** (Section 6): BA phải chuẩn bị trước tài liệu để 2h/tuần của Ops chỉ dùng cho việc review/feedback và usability test; Dev phải bàn giao cuốn chiếu từ giữa Sprint để QA test rải đều trong 5 ngày.
* **Tính năng Defer sau MVP:**
  * Hoãn việc đưa *AI Document Classification* và *OCR tự động nhập liệu (35% thời gian review)* lên Production cho khách hàng, vì vướng rào cản phê duyệt Compliance 8 tuần và rủi ro sai sót trên 41% ảnh chụp thực tế.

---

## 4. Gợi ý Lập luận cho Part 4 (Inspection, Adaptation & Validation - Triệu & Khải)
* **Cách PO xử lý 2 diễn biến ở Sprint 2 Review (Section 7):**
  * **Development 1 (5/8 user không biết bấm gì tiếp theo):** Dù 8 người là mẫu nhỏ, nhưng 5/8 là tỷ lệ rất cao. Nếu user không biết bước tiếp theo thì họ không thể hoàn tất nộp hồ sơ -> Đe dọa trực tiếp Product Goal. **Hành động:** Ưu tiên tạo PBI sửa luồng điều hướng UI/UX (thêm thanh tiến trình, nút CTA rõ ràng, micro-copy hướng dẫn) ngay đầu **Sprint 3** và test lại với user mới.
  * **Development 2 (Stakeholder cấp cao đòi thêm AI Customer Assistant trước Pilot):** **Từ chối đưa vào MVP 8 tuần (Defer sang Post-MVP)**. **Lý do:** (1) Phê duyệt bảo mật cho AI mới không đảm bảo kịp trong 2 Sprint cuối (Section 6, 7) -> Rủi ro trễ hạn Pilot; (2) Capacity cố định (2 Dev, 0.5 QA) đang phải ưu tiên sửa lỗi UX từ Development 1 và chuẩn bị Security Review ở Sprint 4. Có thể đề xuất giải pháp thay thế nhẹ là thêm *FAQ/Tooltips tĩnh theo ngữ cảnh* ngay trong lúc sửa UX ở Sprint 3.
* **2 Chỉ số Đo lường (KPIs) & 1 Điều kiện Phát hành (Release Condition):**
  * *KPI 1:* Tỷ lệ hồ sơ bị follow-up do thiếu/lỗi tài liệu giảm từ `65%` xuống `<= 30%` (hoặc `<= 35%`) trong `4 tuần đầu chạy Controlled Pilot`.
  * *KPI 2:* Thời gian trung vị hoàn tất Initial Document Review giảm từ `7 ngày làm việc` xuống `<= 4.5 - 5 ngày làm việc` trong `4 tuần chạy Controlled Pilot`.
  * *Critical Release Condition (Section 6):* Hoàn tất **Security & Access Control Review** (đảm bảo tài liệu khách hàng lưu đúng môi trường được phê duyệt, phân quyền chuẩn) + **End-to-End Critical Functionality Testing trên Mobile** đạt 0 lỗi nghiêm trọng trước khi mở Pilot.
