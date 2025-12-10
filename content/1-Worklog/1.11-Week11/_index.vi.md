---
title: "Worklog Tuần 11"
date: 2025-11-13
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Mục tiêu tuần 11:

* Nắm rõ kiến trúc Serverless và cách triển khai trên AWS.
* Thành thạo quy trình xây dựng API và Frontend theo mô hình không máy chủ.
* Làm quen với AWS SAM để triển khai hạ tầng bằng mã (Infrastructure as Code).
* Phát triển – triển khai – tự động hóa Microservice trên AWS.
* Cải thiện khả năng tổ chức dữ liệu, tối ưu workflow cho Microservice.
* Tìm hiểu cơ chế Messaging & Eventing trong hệ thống Microservice phân tán.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------- |
| 2   | - Serverless – Lambda tương tác với S3 & DynamoDB – **Thực hành:** <br>&emsp; + Tạo Lambda để xử lý hình ảnh upload lên S3 <br>&emsp; + Khởi tạo Bucket lưu trữ ảnh <br>&emsp; + Viết Policy cho Lambda <br>&emsp; + Kiểm tra hoạt động của Lambda Function <br>&emsp; + Tạo DynamoDB table phục vụ quản lý dữ liệu <br>&emsp; + Tạo Lambda ghi dữ liệu vào DynamoDB <br><br> - Serverless Frontend & API Gateway – **Thực hành:** <br>&emsp; + Triển khai giao diện web lên S3 <br>&emsp; + Tạo bảng DynamoDB để lưu thông tin <br>&emsp; + Xây dựng 3 Lambda: đọc – ghi – xóa dữ liệu <br>&emsp; + Thiết lập API Gateway, method & CORS <br>&emsp; + Kiểm thử API bằng Postman và từ Frontend | 17/11/2025 |  <https://000078.awsstudygroup.com/> <br>  https://000079.awsstudygroup.com/vi/ |
| 3   | - Xây dựng Microservice – **Thực hành:** <br>&emsp; + Tạo CloudFormation Stack làm môi trường thực hành <br>&emsp; + Cấu hình EC2 & Eclipse IDE <br>&emsp; + Khởi tạo dự án Lambda bằng AWS Toolkit <br>&emsp; + Upload hàm Lambda lên AWS từ Eclipse <br>&emsp; + Viết Lambda xử lý ảnh & triển khai lên Console <br>&emsp; + Dùng Maven & PowerShell để triển khai Microservice tự động <br>&emsp; + Tạo kho mã nguồn bằng AWS CodeStar <br>&emsp; + Tích hợp pipeline CI/CD và cập nhật Target Region cho API | 18/11/2025  |  <https://000052.awsstudygroup.com/vi/>  |
| 4   | - Tái cấu trúc dữ liệu & workflow – **Thực hành:** <br>&emsp; + Tạo mới Key Pair & CloudFormation Stack <br>&emsp; + Khởi chạy Windows Instance để phát triển ứng dụng <br>&emsp; + Thêm Global Secondary Index cho DynamoDB <br>&emsp; + Tạo CodeStar repository mới & import ứng dụng từ Eclipse <br>&emsp; + Rebuild Microservice project và cập nhật Target Region <br>&emsp; + Bổ sung IAM Policy cho Role <br>&emsp; + Deploy bằng AWS Pipeline <br>&emsp; + Nâng cấp TripSearch Microservice & bổ sung workflow bằng Step Functions <br>&emsp; + Thêm Lambda vào workflow & mở rộng logic tính toán <br>&emsp; + Tải gói CalculatorStepFull.zip và import vào Eclipse IDE | 19/11/2025 |  <https://000053.awsstudygroup.com/vi/> |
| 5   | AWS SAM – cách viết template, đóng gói và deploy ứng dụng serverless bằng IaC | 20/11/2025 | https://000080.awsstudygroup.com/vi/ |
| 6   | Messaging & Eventing trong Microservices – mô hình hoạt động, các dịch vụ AWS hỗ trợ và cách áp dụng vào kiến trúc phân tán | 21/11/2025 | https://000054.awsstudygroup.com/vi/ |

### Kết quả đạt được tuần 11:
* Hoàn thiện hệ thống Serverless tích hợp Lambda – S3 – DynamoDB: xử lý ảnh, phân quyền bằng IAM Policy, lưu và truy vấn dữ liệu từ DynamoDB, kèm kiểm thử trực tiếp trên Console.
* Xây dựng ứng dụng Serverless kết hợp API Gateway và Frontend: tạo 3 Lambda CRUD, cấu hình đầy đủ CORS, xác thực API bằng Postman và triển khai Frontend lên S3.
* Nắm rõ cơ chế hoạt động và quy trình triển khai ứng dụng bằng AWS SAM: viết template, đóng gói và triển khai stack theo chuẩn IaC.
* Hoàn thành một Microservice đầy đủ: sử dụng CloudFormation để dựng môi trường, phát triển bằng AWS Toolkit trên Eclipse, deploy qua Maven/PowerShell, cấu hình CodeStar & CI/CD Pipeline, cập nhật Target Region và triển khai API.
* Tổ chức lại workflow & dữ liệu cho Microservice: thêm GSI cho DynamoDB, tối ưu mã nguồn, triển khai lại bằng pipeline, mở rộng TripSearch Microservice, xây dựng workflow bằng Step Functions và tích hợp Lambda cho luồng xử lý nâng cao.
* Tiếp cận kiến trúc Messaging & Eventing trong Microservices và cách áp dụng event-driven vào hạ tầng AWS phân tán.

