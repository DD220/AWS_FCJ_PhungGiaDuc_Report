---
title: "Worklog Tuần 9"

date: 2025-11-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---


### Mục tiêu tuần 9:

* Làm chủ AWS KMS và quản lý vòng đời khóa mã hóa.
* Triển khai và quản trị cơ chế backup tự động bằng AWS Backup.
* Nghiên cứu, cấu hình và kết nối bằng AWS Transit Gateway giữa các VPC.
* Làm quen với Docker và triển khai container trên Amazon ECS.


### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------- |
| 3   | - AWS KMS - **Thực hành:** <br>&emsp; + Tạo policy và role, cấu hình group và user mẫu <br>&emsp; + Tạo CMK (Customer Master Key) và thử mã hóa/giải mã object trên S3 <br>&emsp; + Kích hoạt CloudTrail và ghi log; dùng Athena để truy vấn logs | 03/11/2025    |  https://000033.awsstudygroup.com/vi/  |
| 4   | - AWS Backup - **Thực hành:** <br>&emsp; + Chuẩn bị S3/Resource templates và CloudFormation stack cho backup <br>&emsp; + Thiết lập backup plan, cấu hình Backup Vault và notification qua SNS <br>&emsp; + Kiểm tra restore để đảm bảo tính khả dụng | 04/11/2025  |  https://000013.awsstudygroup.com/vi/  <br>  https://000019.awsstudygroup.com/vi/ |
| 5   | - Transit Gateway - **Thực hành:** <br>&emsp; + Tạo KeyPair và chuẩn bị template CloudFormation <br>&emsp; + Khởi tạo Transit Gateway, tạo attachments và route tables <br>&emsp; + Thêm routes vào các VPC route tables và kiểm thử kết nối | 05/11/2025   |  https://000020.awsstudygroup.com/vi/  |
| 6   | - Docker & Amazon ECS - Triển khai ứng dụng: <br>&emsp; + Xây dựng Docker image cho app mẫu <br>&emsp; + Push image lên ECR <br>&emsp; + Tạo task definition và service trên ECS để chạy container | 06/11/2025   |  https://000016.awsstudygroup.com/vi/ <br>  https://000015.awsstudygroup.com/vi/ |


### Kết quả đạt được tuần 9:
* Hoàn thành cấu hình và kiểm thử AWS WAF; thu thập log request để phân tích.
* Tạo và quản lý thành công CMK, áp dụng mã hóa cho object trên S3; theo dõi hoạt động bằng CloudTrail và phân tích log bằng Athena.
* Thiết lập hệ thống AWS Backup đầy đủ, bao gồm Backup Plan, Backup Vault, SNS notification và kiểm tra restore thành công.
* Triển khai Transit Gateway, kết nối nhiều VPC với route hợp lệ và kiểm chứng khả năng trao đổi dữ liệu giữa các mạng.
* Nắm được quá trình đóng gói bằng Docker và triển khai container trên ECS; hiểu kiến trúc task/service của ECS.
