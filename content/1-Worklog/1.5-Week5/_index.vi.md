---
title: "Worklog Tuần 5"
date: 2025-10-06
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---


### Mục tiêu tuần 5:

* Triển khai và vận hành dịch vụ Amazon Lightsail cho website và database.
* Thiết lập Auto Scaling Group để tự động điều chỉnh tài nguyên cho ứng dụng web.
* Làm quen với kiến thức cơ bản về Machine Learning và đào tạo Generative AI  .
* Thực hành phát hiện mối đe dọa và phản ứng sự cố bằng công cụ cloud-native .
* Sử dụng Amazon CloudWatch để giám sát và phân tích hệ thống.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------- |
| 2   | - Amazon Lightsail - **Thực hành:** <br>&emsp; + Triển khai Lightsail Database (MySQL) để lưu trữ dữ liệu ứng dụng  <br>&emsp; + Tạo và cấu hình instance WordPress (Ubuntu, networking, cài đặt WordPress) <br>&emsp; + Triển khai và kiểm tra Prestashop cho cửa hàng trực tuyến | 06/10/2025  | <https://000045.awsstudygroup.com/vi/> |
| 3   | - Auto Scaling Group - **Thực hành:** <br>&emsp; + Chuẩn bị mạng và các thành phần hạ tầng cho kết nối <br>&emsp; + Khởi chạy EC2 và RDS để chạy ứng dụng <br>&emsp; + Nạp dữ liệu vào DB và triển khai app web <br>&emsp; + Thu thập metric cho predictive scaling bằng CloudWatch <br>&emsp; + Tạo Launch Template, cấu hình Load Balancer và Target Group <br>&emsp; + Kiểm tra hoạt động và thử nghiệm manual scaling | 07/10/2025  | <https://000006.awsstudygroup.com/vi/> |
| 4   | - Giới thiệu Machine Learning - **Thực hành:** <br>&emsp; + Tổng quan AI/ML trên AWS <br>&emsp; + Amazon Rekognition và demo use-case xác minh danh tính <br>&emsp; + Tổng quan Generative AI, các ứng dụng và demo <br><br> - Đào tạo Gen AI - **Thực hành:** <br>&emsp; + Khái niệm Generative AI và các kịch bản ứng dụng <br>&emsp; + Prototyping và chia sẻ giải pháp <br>&emsp; + Demo GenAI cho lĩnh vực FSI | 08/10/2025  | <https://specialforce.awsstudygroup.com/#/course/week-14:-introduction-to-machine-learning>  |
| 5   | - Threat detection & Incident response using cloud-native services - **Thực hành:** <br>&emsp; + Chu trình phản ứng sự cố: chuẩn bị, phát hiện, thu thập, cô lập, phân tích, khắc phục, phục hồi <br>&emsp; + Thực hành từng bước xử lý sự cố và bài đánh giá | 09/10/2025   | <https://specialforce.awsstudygroup.com/#/course/week-16:-threat-detection-and-incident-response-using-cloud-native-services> |
| 6   | - Amazon CloudWatch - **Thực hành:** <br>&emsp; + Truy vấn và phân tích Metrics <br>&emsp; + Thực hiện các phép toán trên metrics và tạo Dynamic Labels <br>&emsp; + Sử dụng Logs Insight để đọc logs <br>&emsp; + Lọc metrics, cấu hình Alarms và xây dựng Dashboards để giám sát hệ thống | 10/10/2025   | <https://000008.awsstudygroup.com/vi/>|


### Kết quả đạt được tuần 5:
* Amazon Lightsail
 * Đã triển khai thành công cơ sở dữ liệu MySQL trên Lightsail phục vụ lưu trữ ứng dụng.
 * Cài đặt và cấu hình instance WordPress trên Ubuntu, hoàn thiện phần networking và môi trường WordPress.
 * Triển khai Prestashop cho website thương mại điện tử và kiểm tra hoạt động ổn định.
* Auto Scaling Group
 * Hoàn tất cấu hình mạng, khởi chạy EC2 và RDS, nạp dữ liệu và đưa ứng dụng web vào chạy thử.
 * Tạo Launch Template, cấu hình Load Balancer + Target Group và triển khai Auto Scaling Group để quản lý tải.
 * Chuẩn bị metric cho predictive scaling bằng CloudWatch và thử nghiệm manual scaling; nhận thông báo qua email khi cần.
* Machine Learning & Generative AI
 * Nắm được các khái niệm cơ bản về AI/ML trên AWS; thử nghiệm Amazon Rekognition cho nhận diện/verify.
 * Tiếp cận Generative AI, tìm hiểu RAG và các mô hình agent; hoàn thành quiz đánh giá.
* Threat Detection & Incident Response
 * Hiểu và thực hành chu trình phản ứng sự cố: chuẩn bị, phát hiện, thu thập, cô lập, phân tích, khắc phục và phục hồi.
 * Biết cách sử dụng dịch vụ bảo mật native của AWS để phát hiện và xử lý mối đe dọa.
* Amazon CloudWatch
 * Thành thạo truy vấn, lọc và phân tích Metrics/Logs; cấu hình Alarms và xây dựng Dashboards để giám sát hệ thống.
