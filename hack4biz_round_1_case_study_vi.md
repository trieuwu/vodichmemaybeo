## 1. Bối cảnh Kinh doanh (Business Background)

Bank X là một ngân hàng thương mại giả định tại Việt Nam phục vụ nhóm khách hàng cá nhân và doanh nghiệp vừa và nhỏ (SMEs). Ngân hàng cung cấp các khoản vay kinh doanh thông qua mạng lưới chi nhánh và nền tảng ngân hàng trực tuyến (online banking platform). Mặc dù Bank X đã số hóa phần lớn quy trình đăng ký tín dụng (credit application process), khách hàng vẫn liên tục phản ánh những khó khăn trong việc chuẩn bị hồ sơ tài liệu, nộp đơn đăng ký và nhận thông tin cập nhật trạng thái.

Ban lãnh đạo ngân hàng tin rằng việc cải thiện trải nghiệm này có thể nâng cao mức độ hài lòng của khách hàng, giảm thiểu các công việc vận hành không cần thiết và giúp dịch vụ trở nên dễ tiếp cận hơn. Tuy nhiên, ban lãnh đạo vẫn chưa chắc chắn vấn đề nào nên được ưu tiên giải quyết trước, cũng như liệu các cải tiến nên áp dụng tự động hóa (automation), trí tuệ nhân tạo (AI), tái thiết kế quy trình (process redesign), hay kết hợp các phương pháp này.

Bank X đã áp dụng Scrum vào việc phát triển sản phẩm số. Ban lãnh đạo kỳ vọng Scrum Team được giao nhiệm vụ sẽ sử dụng phương pháp tiếp cận lặp (iterative) và dựa trên bằng chứng (evidence-based approach) để xác định một cải tiến mang lại giá trị cao, chuyển giao các Product Increment có thể sử dụng được, và thích ứng linh hoạt với các phản hồi (feedback).

**Thử thách của bạn:**

Làm thế nào để Bank X tái thiết kế trải nghiệm đăng ký tín dụng SME nhằm giảm bớt công sức không cần thiết cho khách hàng và sự kém hiệu quả trong vận hành, đồng thời sử dụng Scrum để chuyển giao và kiểm chứng (validate) một giải pháp sáng tạo, khả thi? Scrum Team của bạn có 8 tuần, được chia thành 4 Sprint (mỗi Sprint kéo dài 2 tuần), để chuẩn bị một MVP khả thi cho đợt triển khai thử nghiệm có kiểm soát (controlled pilot).

Team của bạn không bắt buộc phải cải thiện mọi giai đoạn trong hành trình khách hàng (customer journey). Bạn phải ưu tiên cơ hội mang lại giá trị lớn nhất và chứng minh giải pháp của mình có thể được phát triển tăng trưởng từng phần (incrementally) như thế nào.

### *Hướng dẫn (Instructions)*

* Các đội thi phải nộp một bài giải thống nhất, giải quyết đầy đủ cả bốn phần.
* **Tối đa 6 trang.** Nếu vượt quá giới hạn này, phần nội dung từ sau trang thứ 6 sẽ không được chấm điểm.
* Tất cả các đề xuất phải liên quan đến cùng một cải tiến sản phẩm hoặc dịch vụ đã chọn.
* Sử dụng các dữ liệu/bằng chứng được cung cấp trong đề bài và tuân thủ mọi ràng buộc triển khai (implementation constraints).
* Không sử dụng video, ảnh GIF và các đối tượng nhúng (embedded objects), vì chúng không thể chèn một cách ổn định vào file `.docx`.
* Được phép sử dụng bảng biểu, biểu đồ, wireframes/mockups, roadmaps và các hình ảnh trực quan tương tự để trình bày ý tưởng tốt hơn. Hình ảnh trực quan không bị chấm điểm về mặt chất lượng thiết kế thẩm mỹ, và tất cả các bảng biểu, hình vẽ phải đọc rõ được ở mức thu phóng (zoom) 100%.
* Không yêu cầu phải viết code (coding).
* Không áp đặt giải pháp hay lựa chọn công nghệ bắt buộc nào.

### *Yêu cầu Nộp bài (Submission Requirements)*

* 01 file định dạng `.docx`, dung lượng tối đa **5 MB**.
* Không bắt buộc phải có danh mục tài liệu tham khảo riêng; hãy trích dẫn dữ liệu của case trực tiếp trong bài viết (inline citation, ví dụ: Exhibit A, Section 6). Nếu có sử dụng nguồn bên ngoài, hãy liệt kê ngắn gọn ở cuối bài (tối đa 5 mục; không tính vào giới hạn số trang). Không được phép dùng phụ lục (Appendices).
* Định dạng: Khổ A4, font Times New Roman cỡ 12 pt, giãn dòng (line spacing) 1.5, căn lề (margins) 2–2.5 cm. Trong bảng biểu có thể sử dụng giãn dòng đơn (single spacing) và cỡ chữ 10–11 pt.
* Tên file: `Team Name_Round 1` (ví dụ: `Agile Eagles_Round 1.docx`).
* Bất kỳ file bài làm nào chưa được tải lên khi hệ thống tự động thu bài sau 120 phút sẽ không được chấm điểm, trừ khi lỗi tải lên đã được báo cáo theo đúng quy định trong Sổ tay Thí sinh (Candidate Booklet).

---

## 2. Hành trình Khách hàng Hiện tại (Current Customer Journey)

Quy trình đăng ký tín dụng hiện tại của Bank X bao gồm 5 giai đoạn chính.

| Giai đoạn (Stage) | Hoạt động của khách hàng và nhân viên | Khó khăn ghi nhận được |
| :--- | :--- | :--- |
| **1. Tìm hiểu yêu cầu hồ sơ (Discover requirements)** | Chủ doanh nghiệp SME xem thông tin khoản vay và các yêu cầu về hồ sơ tài liệu qua website của ngân hàng hoặc chuyên viên tư vấn tại chi nhánh. | Yêu cầu hồ sơ thay đổi tùy theo sản phẩm vay và hồ sơ doanh nghiệp (business profile). Một số khách hàng gặp khó khăn trong việc xác định những tài liệu nào áp dụng cho trường hợp của họ. |
| **2. Chuẩn bị và tải lên tài liệu (Prepare and upload documents)** | Người đăng ký chuẩn bị các tài liệu chứng minh, tải lên qua cổng thông tin (portal) và nộp đơn đăng ký. | Một số tệp đính kèm bị thiếu, không đọc được (mờ/lỗi) hoặc bị phân loại sai danh mục. |
| **3. Kiểm tra tính đầy đủ (Completeness verification)** | Nhân viên ngân hàng rà soát hồ sơ đã nộp và yêu cầu chỉnh sửa/bổ sung khi cần thiết. | Người đăng ký có thể nhận được các yêu cầu bổ sung (follow-up requests) sau khi đã nộp đơn và phải tải lên thêm tài liệu. |
| **4. Theo dõi tiến độ hồ sơ (Track application progress)** | Người đăng ký chờ cập nhật và liên hệ bộ phận hỗ trợ khách hàng (Customer Support) hoặc chuyên viên quan hệ khách hàng (Relationship Manager - RM) khi cần. | Thông tin về trạng thái hồ sơ rất hạn chế, dẫn đến việc khách hàng phải hỏi đi hỏi lại nhiều lần và cảm thấy bất an, không chắc chắn. |
| **5. Thẩm định tài liệu sơ bộ (Initial document review)** | Nhân viên vận hành tín dụng (Credit Operations) kiểm tra các tài liệu đã nộp và nhập thủ công các thông tin liên quan vào hệ thống nội bộ. | Việc nhập liệu lặp đi lặp lại và xác minh tài liệu tiêu tốn nhiều thời gian của nhân viên. Tiềm ẩn rủi ro sai sót do con người (human error) trong quá trình nhập liệu. |

Quy trình trong phạm vi đề bài kết thúc ở bước thẩm định tài liệu sơ bộ (Initial document review). Việc thẩm định tín dụng chính thức và quyết định cho vay cuối cùng diễn ra sau đó và nằm ngoài phạm vi (scope) của thử thách này.

---

## 3. Người dùng Mục tiêu và Các bên liên quan (Target Users and Stakeholders)

| Users / Stakeholders | Nhu cầu (Needs) |
| :--- | :--- |
| **Khách hàng chính (Chủ doanh nghiệp SME)** | Chủ các doanh nghiệp nhỏ đang tìm kiếm nguồn vốn cho hoạt động kinh doanh. Họ thường ít quen thuộc với các thủ tục giấy tờ ngân hàng và muốn giảm thiểu tối đa các công việc hành chính phức tạp. |
| **Khách hàng quay lại (SME đã có kinh nghiệm vay)** | Người đăng ký đã từng hoàn tất hồ sơ vay tín dụng trước đây và có thể đã quen với các yêu cầu của ngân hàng. |
| **Nhân viên Relationship Manager (RM) / Customer Support** | Hỗ trợ người đăng ký, giải đáp thắc mắc và điều phối các yêu cầu bổ sung hồ sơ (follow-up requests). |
| **Nhân viên vận hành tín dụng (Credit Operations)** | Kiểm tra hồ sơ tài liệu đã nộp, ghi nhận thông tin vào hệ thống và xác định các tài liệu bị thiếu hoặc không nhất quán. |
| **Ban lãnh đạo Ngân hàng (Bank Management)** | Tìm cách cân bằng giữa trải nghiệm khách hàng, hiệu quả vận hành, chi phí triển khai và các nghĩa vụ tuân thủ (compliance obligations). |

---

## 4. Dữ liệu Vận hành (Operational Data)

Các số liệu dưới đây phản ánh **01 tháng điển hình** trong hoạt động vận hành của Bank X.

### Exhibit A - Xử lý Hồ sơ Đăng ký (Application Processing)

| Chỉ số (Metric) | Giá trị (Value) |
| :--- | :--- |
| Số hồ sơ đăng ký tín dụng nhận được | 1.200 hồ sơ/tháng |
| Số hồ sơ phải liên hệ yêu cầu bổ sung tài liệu còn thiếu (missing-document follow-up) | 780 (65%) |
| Tỷ lệ hồ sơ bị thiếu được khách hàng bổ sung/sửa lại trong vòng 1 ngày làm việc | 68% |
| Thời gian trung bình nhân viên xử lý mỗi ca follow-up (liên hệ khách hàng và kiểm tra lại hồ sơ nộp bổ sung) | 10 phút |
| Thời gian trung vị (Median duration) từ lúc nộp đơn ban đầu đến khi hoàn tất thẩm định tài liệu sơ bộ - tính trên toàn bộ hồ sơ | 7 ngày làm việc |
| Thời gian trung vị — đối với hồ sơ KHÔNG cần follow-up bổ sung | 4 ngày làm việc |
| Thời gian trung vị — đối với hồ sơ CÓ follow-up bổ sung | 8 ngày làm việc |
| Tỷ lệ hồ sơ được khởi tạo trên thiết bị di động (mobile devices) | 78% |

Các hồ sơ cần follow-up nhìn chung mất nhiều thời gian xử lý hơn. Tuy nhiên, các yếu tố khác cũng có thể góp phần gây ra sự chậm trễ này, do đó vẫn chưa rõ chính xác có thể tiết kiệm được bao nhiêu thời gian xử lý thông qua tự động hóa (automation).

### Exhibit B - Phân khúc Khách hàng (Customer Segmentation)

| Phân khúc (Segmentation) | Số hồ sơ hàng tháng | Tỷ lệ cần follow-up bổ sung tài liệu thiếu |
| :--- | :--- | :--- |
| Khách hàng đăng ký lần đầu (First-time applicants) | 800 | 75% |
| Khách hàng quay lại (Returning applicants) | 400 | 45% |
| **Tổng cộng** | **1.200** | **65%** |

### Exhibit C - Trạng thái Hồ sơ và Hỗ trợ Khách hàng (Application Status and Support)

| Chỉ số (Metric) | Giá trị (Value) |
| :--- | :--- |
| Số lượt khách hàng liên hệ hỏi về trạng thái hồ sơ | 400 lượt/tháng |
| Thời gian nhân viên xử lý trung bình cho mỗi lượt hỏi | 5 phút |
| Tỷ lệ lượt hỏi được xác định là hỏi lặp lại về trạng thái trong vòng 7 ngày | 26% |
| Tổng số phiên truy cập (sessions) ứng dụng Mobile Banking nói chung trên tất cả các dịch vụ ngân hàng | 21.000 phiên/tháng |

Một cuộc khảo sát thuận tiện (convenience survey) riêng biệt cho thấy 21 trên 25 người tham gia khảo sát quan tâm đến việc nhận thông báo chủ động (proactive notifications) về trạng thái hồ sơ đăng ký.

Tuy nhiên, kích thước mẫu nhỏ và phương pháp chọn mẫu của cuộc khảo sát này làm hạn chế mức độ tin cậy khi khái quát hóa kết quả cho toàn bộ người đăng ký.

### Exhibit D - Hoạt động Thẩm định Tài liệu (Document Review Operations)

| Chỉ số (Metric) | Giá trị (Value) |
| :--- | :--- |
| Thời gian thẩm định sơ bộ trung bình | 12 phút/hồ sơ |
| Tổng công sức (effort) thẩm định sơ bộ | 240 giờ công nhân viên/tháng (staff-hours/month) |
| Tỷ lệ thời gian thẩm định dành cho việc nhập liệu thủ công (manual data transcription) | 35% |
| Tỷ lệ tài liệu tải lên là bản scan dạng hình ảnh hoặc ảnh chụp | 41% |

Trước đây, Bank X đã từng thử nghiệm một bản prototype phân loại tài liệu bằng AI (AI-based document classification prototype). Bản prototype này đã phân loại chính xác 48 trên 50 tài liệu thử nghiệm sạch, được khởi tạo dưới dạng kỹ thuật số (clean, digitally generated test documents), tương đương độ chính xác 96%. Tuy nhiên, công nghệ này vẫn chưa được đánh giá đầy đủ trên các bản scan tài liệu thực tế, ảnh chụp bằng điện thoại, file bị lỗi (corrupted files) hoặc các bộ hồ sơ nộp thiếu.

---

## 5. Hệ thống Hiện có và Năng lực Dịch vụ (Existing Systems and Service Capabilities)

Bank X hiện đang vận hành các hệ thống sau:

| Hệ thống / Năng lực | Trạng thái hiện tại |
| :--- | :--- |
| **Cổng đăng ký trực tuyến (Online application portal)** | Hỗ trợ người dùng đã xác thực (authenticated users), nộp đơn đăng ký, lưu bản nháp cơ bản (basic draft saving) và tải lên tài liệu. |
| **Lưu trữ tài liệu (Document storage)** | Kho lưu trữ bảo mật dành cho các tài liệu chứng minh được tải lên. |
| **Định dạng tài liệu được chấp nhận** | PDF, JPG/JPEG và PNG, với dung lượng tối đa 10 MB mỗi file. |
| **Quy định về hồ sơ tài liệu (Document requirements)** | Được quản lý nội bộ và thay đổi tùy theo sản phẩm vay cũng như đặc điểm của người đăng ký. |
| **Kiểm tra hợp lệ cơ bản (Basic validation)** | Kiểm tra định dạng và dung lượng file, nhưng không xác minh toàn diện được liệu tất cả các tài liệu bắt buộc đã được đính kèm đầy đủ hay chưa. |
| **Hệ thống trạng thái hồ sơ (Application status system)** | Theo dõi tiến độ hồ sơ trong nội bộ. Thông tin trạng thái ở mức hạn chế được xuất (export) sang hệ thống phía khách hàng (customer-facing system) mỗi ngày một lần. |
| **Giao tiếp khách hàng (Customer communications)** | Hỗ trợ gửi email giao dịch (transactional emails). Các kênh thông báo bổ sung khác cần phải được đánh giá thêm. |
| **Phân loại tài liệu bằng AI (AI document classification)** | Chỉ mới ở mức bản thử nghiệm (experimental prototype). Mức độ sẵn sàng để đưa vào vận hành thực tế (production readiness) chưa được xác lập. |
| **Phê duyệt tín dụng (Credit approval)** | Vận hành qua một quy trình kiểm soát riêng biệt và không thể chỉnh sửa trong phạm vi dự án này. |

Các đội thi có thể đề xuất cải tiến những hệ thống hiện có, xây dựng thêm các tính năng mới gọn nhẹ (lightweight capabilities), các quy trình có nhân viên hỗ trợ (staff-assisted processes), hoặc kết hợp các hướng tiếp cận này.

---

## 6. Năng lực Đội ngũ và Các Ràng buộc (Team Capacity and Constraints)

### Năng lực chuyển giao (Delivery capacity - Cố định)

| Nguồn lực (Resource) | Mức độ sẵn sàng (Availability) |
| :--- | :--- |
| **Product Owner** | 1 người, toàn thời gian (full-time) |
| **Scrum Master** | 1 người, toàn thời gian (full-time) |
| **Software Developers (Dev)** | 2 người, toàn thời gian (full-time) |
| **QA Engineer** | 1 người, bán thời gian ở mức 50% (khoảng 5 ngày làm việc mỗi Sprint) |
| **Business Analyst (BA)** | 1 người, toàn thời gian (full-time) |
| **Nhân viên Vận hành Ngân hàng (RM và Credit Operations)** | Tối đa tổng cộng 2 giờ mỗi tuần, dành cho việc tham vấn, đưa feedback và tham gia các buổi kiểm thử tính khả dụng (usability sessions) |

### Quy định triển khai theo Scrum (Scrum delivery arrangement)

* Ngân hàng đã phê duyệt khung thời gian phát triển 8 tuần, được tổ chức thành **4 Sprint (mỗi Sprint 2 tuần)**. Khoảng thời gian 8 tuần này đã bao gồm cả việc kiểm chứng (validation) và chuẩn bị cho đợt triển khai thử nghiệm có kiểm soát (controlled pilot).
* Scrum Team phải làm việc hướng tới một **Product Goal** rõ ràng.
* Mỗi Sprint đều kỳ vọng tạo ra một **Product Increment** có thể sử dụng được và thỏa mãn **Definition of Done (DoD)**. Một Increment không nhất thiết phải được phát hành (release) ngay lập tức cho khách hàng.
* Các buổi **Sprint Review** có sự tham gia của các stakeholders phù hợp từ phía ngân hàng và có thể dẫn đến những điều chỉnh trong **Product Backlog**.
* Các buổi **Sprint Retrospective** được sử dụng để xác định những điểm cần cải thiện trong cách thức làm việc của team.
* Đợt triển khai thử nghiệm có kiểm soát (controlled customer pilot) với khách hàng có thể bắt đầu sau Sprint thứ 4 nếu giải pháp đáp ứng được các yêu cầu phát hành (release requirements) của ngân hàng.

### Ràng buộc triển khai (Implementation constraints)

| Ràng buộc (Constraint) | Yêu cầu (Requirement) |
| :--- | :--- |
| **Thẩm quyền ra quyết định (Decision authority)** | Product Owner có thể điều chỉnh thứ tự ưu tiên và phạm vi (scope) của các Product Backlog items khi có thêm bằng chứng mới. Team không thể kéo dài deadline hay tăng thêm delivery capacity. |
| **Hạ tầng hiện có (Existing infrastructure)** | Các đội nên tái sử dụng các hệ thống hiện có ở những nơi thiết thực. |
| **Bảo mật (Security)** | Tài liệu của khách hàng phải được giữ trong các môi trường đã được phê duyệt, với cơ chế phân quyền (authorization) và kiểm soát truy cập (access controls) phù hợp. |
| **Dịch vụ bên ngoài (External services)** | Các dịch vụ bên thứ ba (third-party services) mới và việc tích hợp AI lên môi trường thực tế (production AI integrations) đòi hỏi phải có sự phê duyệt về bảo mật và tuân thủ (security and compliance approval) từ ban lãnh đạo ngân hàng; việc được phê duyệt trong vòng 8 tuần là **không được đảm bảo**. |
| **Yêu cầu trước khi ra mắt (Launch requirement)** | Phải hoàn tất việc rà soát bảo mật (security review) và kiểm thử các chức năng trọng yếu (critical functionality testing) trước khi chạy pilot. |

---

## 7. Tình huống Bổ sung (Additional Scenario)

Giả sử Scrum Team của bạn đã hoàn thành **Sprint thứ 2** và đã demo một Increment ban đầu của giải pháp đề xuất cho các stakeholders của ngân hàng.

Trong buổi **Sprint Review**, có hai diễn biến quan trọng phát sinh:

### *Diễn biến 1: Phản hồi bất ngờ từ người dùng (Unexpected user feedback)*

*Trong một buổi đánh giá tính khả dụng (usability evaluation) quy mô nhỏ với sự tham gia của 8 người dùng mục tiêu, có 5 người tham gia gặp khó khăn trong việc hiểu họ cần phải thực hiện thao tác gì tiếp theo sau khi tương tác với Increment ban đầu này. Các quan sát chỉ ra một vấn đề tiềm ẩn về tính khả dụng (usability issue), nhưng cỡ mẫu quá nhỏ để khẳng định mức độ phổ biến của vấn đề này trên diện rộng.*

### *Diễn biến 2: Yêu cầu mới từ Stakeholder (New stakeholder request)*

*Một stakeholder cấp cao mảng kinh doanh yêu cầu team bổ sung thêm một trợ lý khách hàng tích hợp AI (AI-powered customer assistant) trước đợt pilot 8 tuần, vì tin rằng tính năng này sẽ giúp cải thiện trải nghiệm khách hàng. Tuy nhiên, tính năng này không nằm trong phạm vi MVP ban đầu. Việc được phê duyệt đưa lên môi trường thực tế (production approval) cho một tích hợp AI mới cũng không được đảm bảo trong hai Sprint còn lại.*

Thời hạn chuyển giao (delivery deadline), năng lực của team (team capacity) và các yêu cầu bảo mật **vẫn giữ nguyên không đổi**.

Product Owner phải quyết định xem những phát hiện và yêu cầu mới này sẽ tác động như thế nào đến Product Backlog và công việc trong tương lai.

---

# Bài tập của Bạn (Your Assignment)

Team của bạn phải nộp **MỘT bản đề xuất tích hợp duy nhất (ONE integrated proposal)**, bao gồm các phần dưới đây. Bạn có thể tập trung vào bất kỳ vấn đề quan trọng nào trong hành trình khách hàng, miễn là quyết định của bạn được củng cố bởi các bằng chứng dữ liệu trong bài.

Được phép đưa ra các giả định (assumptions) hợp lý nhưng phải nêu rõ ràng. Không yêu cầu viết code hay vẽ sơ đồ kỹ thuật phức tạp.

### Phần 1: Xác định Vấn đề & Product Goal (Problem Identification & Product Goal)

Xác định **MỘT vấn đề** mà team của bạn ưu tiên giải quyết trong hành trình đăng ký tín dụng SME của Bank X.

Câu trả lời của bạn phải:

1. Xác định nhóm người dùng bị ảnh hưởng và định nghĩa rõ vấn đề đã chọn.
2. Củng cố lý do ưu tiên vấn đề đó bằng ít nhất 2 bằng chứng (evidence) liên quan từ đề bài.
3. Định nghĩa một **Product Goal** mô tả kết quả tương lai mong muốn (desired future outcome) và một giả định quan trọng (important assumption) cần được kiểm chứng (validation).

### Phần 2: Tái thiết kế Dịch vụ Sáng tạo (Creative Service Redesign)

Đề xuất một cải tiến dịch vụ mang tính đổi mới nhằm giải quyết vấn đề bạn đã chọn.

Câu trả lời của bạn phải:

1. Mô tả giải pháp đề xuất và giá trị mà nó tạo ra cho khách hàng hoặc nhân viên ngân hàng.
2. Giải thích luồng công việc đã được tái thiết kế (redesigned workflow), chỉ rõ những điểm thay đổi so với trải nghiệm hiện tại.
3. Giải thích cách bản đề xuất giải quyết được nguyên nhân gốc rễ của vấn đề (underlying problem).

Các đội có thể đề xuất giải pháp ứng dụng AI hoặc không dùng AI, có thể bao gồm tự động hóa (automation), tính năng số mới hoặc cải tiến tính năng cũ, cải tiến quy trình vận hành, hoặc kết hợp các phương pháp này. Tính sáng tạo sẽ được đánh giá dựa trên mức độ phù hợp, tính hiệu quả và khả năng giải quyết vấn đề đã xác định của giải pháp, thay vì chấm điểm dựa trên độ hào nhoáng của công nghệ được sử dụng.

### Phần 3: Lập kế hoạch & Thực thi MVP dựa trên Scrum (Scrum-Based MVP Planning & Execution)

Phát triển một đề xuất chuyển giao sản phẩm bao gồm các mục sau:

#### A. Product Backlog

Xác định **4 Product Backlog items được sắp xếp theo thứ tự ưu tiên** cho giải pháp của bạn.

Với mỗi item, hãy cung cấp:

1. Mô tả ngắn gọn về tính năng hoặc công việc.
2. Giá trị mang lại cho khách hàng hoặc cho doanh nghiệp (customer or business value).
3. Mức độ ưu tiên tương đối của nó (relative priority).

Đối với item có độ ưu tiên cao nhất, hãy cung cấp một tiêu chí chấp nhận cụ thể, có thể kiểm thử được (**specific, testable acceptance criterion**).

#### B. Chuyển giao Tăng trưởng từng phần (Incremental Delivery)

Trong Scrum, mỗi **Sprint Goal** được thiết lập trong buổi **Sprint Planning** của chính Sprint đó. Do vậy, kế hoạch của bạn cần:

1. Giải thích Product Increment có thể sử dụng được hoặc cải tiến nào mà team dự kiến sẽ demo sau mỗi Sprint.
2. Nêu rõ **Sprint Goal** cho Sprint 1 và mục tiêu dự báo (forecast objective) cho các Sprint 2–4, đồng thời ghi nhận rằng các mục tiêu này sẽ được tinh chỉnh (refined) khi team học hỏi thêm được thông tin mới trong quá trình làm.
3. Tính toán hợp lý đến việc triển khai, kiểm thử (testing), các yếu tố phụ thuộc (dependencies), năng lực của team (team capacity) đã nêu và deadline cố định 8 tuần.

Team không bị kỳ vọng phải cam kết trước một **Sprint Backlog** cố định cho cả 8 tuần.

#### C. Definition of Done (DoD)

Đề xuất ít nhất 3 điều kiện chất lượng liên quan mà tất cả các công việc sản phẩm khi hoàn thành phải thỏa mãn để đủ điều kiện được coi là một phần của một Increment có thể sử dụng được.

#### D. Tính khả thi và Phạm vi (Feasibility and Scope)

Xác định các sự phụ thuộc hoặc rủi ro chính trong quá trình triển khai (1–3 rủi ro), xếp hạng theo mức độ quan trọng, và giải thích cách quản lý rủi ro nghiêm trọng nhất. Xác định ít nhất 1 tính năng cần hoãn lại sau giai đoạn MVP (defer beyond the MVP) và giải thích lý do tại sao.

*Định dạng gợi ý: Các bảng biểu gọn gàng và giải thích ngắn gọn.*

### Phần 4: Thanh tra, Thích nghi và Kiểm chứng (Inspection, Adaptation, and Validation)

Xem xét các thông tin mới phát sinh trong buổi **Sprint Review thứ 2** ở Mục 7 (Section 7).

Câu trả lời của bạn phải:

1. Giải thích cách **Product Owner** nên phản hồi trước hai diễn biến ở Mục 7, quyết định này bảo vệ **Product Goal** như thế nào, và điều đó có ý nghĩa gì đối với công việc trong hai Sprint còn lại.
2. Xác định 2 chỉ số đo lường thành công (measurable success indicators), bao gồm mục tiêu cụ thể (target) và giai đoạn đánh giá (evaluation period), cùng với 1 bài kiểm thử hoặc điều kiện phát hành trọng yếu (critical test or release condition) bắt buộc phải vượt qua trước khi triển khai thử nghiệm có kiểm soát (controlled pilot).
