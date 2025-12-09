---
title: "Worklog Tuần 6"
date: 2025-10-13
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---



### Mục tiêu tuần 6:

* Xây dựng ứng dụng web với tính sẵn sàng cao (High Availability).
* Thực hành Amazon Route53 cho quản lý DNS.
* Sử dụng AWS CLI để quản lý tài nguyên trên EC2.
* Phát triển và triển khai AWS Lambda functions.
* Chuyển đổi và di chuyển máy ảo từ on-premises lên AWS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Amazon Route53 - **Thực hành:** <br>&emsp; + Tạo KeyPair để bảo mật kết nối <br>&emsp; + Xây dựng CloudFormation Template tự động hóa <br>&emsp; + Cấu hình Security Group để kiểm soát traffic <br>&emsp; + Kết nối thông qua RDGW bằng RDP và đăng nhập máy chủ <br>&emsp; + Triển khai Microsoft Active Directory (AD) <br>&emsp; + Thiết lập Outbound Rules, Resolver Rules, Inbound Endpoints cho DNS Resolution | 13/10/2025   | 13/10/2025      | <https://000010.awsstudygroup.com/vi/> |
| 3   | - AWS CLI trên EC2 - **Thực hành:** <br>&emsp; + Cài đặt AWS CLI cho Linux <br>&emsp; + Liệt kê và quản lý tài nguyên EC2 qua CLI <br>&emsp; + Sử dụng CLI để tương tác với S3, SNS <br>&emsp; + Tạo và quản lý IAM identities <br>&emsp; + Khởi tạo VPC, Internet Gateway, EC2 Instance hoàn toàn bằng dòng lệnh | 14/10/2025   | 14/10/2025      | <https://000011.awsstudygroup.com/vi/> | <https://000021.awsstudygroup.com/> |
| 4   | - AWS VM Import/Export - **Thực hành:** <br>&emsp; + Thiết lập VMware Workstation để quản lý máy ảo <br>&emsp; + Di chuyển máy ảo từ on-premises lên AWS thành công <br>&emsp; + Khởi tạo EC2 Instance từ AMI được nhập <br>&emsp; + Cấu hình S3 Bucket ACL cho quản lý truy cập <br>&emsp; + Xuất máy ảo từ EC2 Instance/AMI về máy cục bộ | 16/10/2025   | 16/10/2025      | <https://000014.awsstudygroup.com/vi/> |
| 5   | - AWS Lambda - **Thực hành:** <br>&emsp; + Chuẩn bị VPC, Security Group, EC2 Instance <br>&emsp; + Tích hợp Slack Webhook để tăng cường giám sát <br>&emsp; + Gán Tag cho Instance <br>&emsp; + Tạo IAM Role cho Lambda <br>&emsp; + Phát triển Lambda functions (Start/Stop) để tự động điều khiển EC2 <br>&emsp; + Xác minh hoạt động và dọn dẹp tài nguyên | 17/10/2025   | 17/10/2025      | <https://000022.awsstudygroup.com/vi/> |
| 6   | - Highly Available Web Application Workshop - **Thực hành:** <br>&emsp; + Chuẩn bị Security Group cho EC2 và Database <br>&emsp; + Khởi chạy EC2 và RDS Database <br>&emsp; + Cài đặt WordPress trên EC2 <br>&emsp; + Xây dựng Auto Scaling bao gồm: AMI, Launch Template, Target Group, Load Balancer, Auto Scaling Group <br>&emsp; + Snapshot Database và Recovery <br>&emsp; + Tích hợp CloudFront để tăng tốc | 15/10/2025   |


### Kết quả đạt được tuần 6:
* Amazon Route53
 * Khởi tạo thành công KeyPair, CloudFormation Template và Security Group phục vụ cho kiến trúc mạng.
 * Thiết lập kết nối từ xa thông qua RDGW/RDP và truy cập máy chủ.
 * Triển khai Microsoft Active Directory và cấu hình các thành phần DNS (Outbound/Inbound Endpoints, Resolver Rules) trong Route53.
* AWS CLI trên EC2
 * Cài đặt AWS CLI trên Linux và thực hành các lệnh quản lý EC2, S3, SNS, IAM, VPC.
 * Nắm vững cách tự động hóa tạo Internet Gateway và EC2 Instance bằng dòng lệnh CLI.
* Highly Available Web Application Workshop
 * Xây dựng ứng dụng web WordPress với kiến trúc High Availability bao gồm Auto Scaling, Load Balancer, CloudFront.
 * Cấu hình AMI, Launch Template, Target Group để hỗ trợ tự động mở rộng theo nhu cầu.
 * Thực hành Snapshot và Recovery Database, quản lý tài nguyên hiệu quả.
* AWS VM Import/Export
 * Chuyển đổi thành công máy ảo VMware Workstation lên AWS EC2 Instance.
 * Cấu hình S3 Bucket ACL và thực hành xuất máy ảo về máy cục bộ, hiểu rõ quy trình di chuyển hybrid.
* AWS Lambda
 * Tạo Lambda functions (Start/Stop) để tự động quản lý trạng thái EC2, tích hợp Slack Webhook cho giám sát.
 * Xác minh hoạt động thành công và dọn dẹp tài nguyên sau khi hoàn tất.    