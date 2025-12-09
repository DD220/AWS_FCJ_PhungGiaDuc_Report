---
title: "Worklog Tuần 7"
date: 2025-10-20
weight: 7
chapter: false
pre: " <b> 1.7. </b> "
---


### Mục tiêu tuần 7:

* Tổ chức tài nguyên AWS bằng Tag và Resource Groups.
* Áp dụng AWS Systems Manager cho tự động hóa và vận hành.
* Quản lý quyền truy cập tài nguyên thông qua IAM Policy.
* Thực hành giám sát hệ thống với Amazon CloudWatch và Grafana.
* Sử dụng Session Manager để truy cập máy chủ an toàn.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Amazon CloudWatch và Grafana - **Thực hành:** <br>&emsp; + Khởi tạo VPC, Subnets, Security Groups, EC2, IAM User và Role <br>&emsp; + Cài đặt Grafana trên EC2 bằng SSH kết nối <br>&emsp; + Tích hợp CloudWatch vào Grafana để giám sát tập trung | 20/10/2025   | 20/10/2025      | <https://000029.awsstudygroup.com/vi/> |
| 3   | - AWS Systems Manager – Patch Manager - **Thực hành:** <br>&emsp; + Chuẩn bị VPC, Subnet, EC2 Windows, IAM Role <br>&emsp; + Cấu hình Patch Manager để quản lý bản vá <br>&emsp; + Sử dụng Run Command tự động thực thi các lệnh trên EC2 | 22/10/2025   | 22/10/2025      | <https://000031.awsstudygroup.com/vi/>  |
| 4   | - Tag và Resource Groups - **Thực hành:** <br>&emsp; + Tạo EC2 Instance và áp dụng Tag <br>&emsp; + Sử dụng Resource Groups để lọc tài nguyên theo Tag <br>&emsp; + Thiết lập IAM Policy để kiểm soát quyền truy cập dựa trên Tag <br>&emsp; + Thử nghiệm Switch Role và kiểm tra chính sách | 21/10/2025   | 21/10/2025      | <https://000027.awsstudygroup.com/vi/> <https://000028.awsstudygroup.com/vi/> |
| 5   | - AWS Systems Manager – Session Manager - **Thực hành:** <br>&emsp; + Tạo VPC, Subnet, Security Group, EC2 Linux, IAM Role <br>&emsp; + Kích hoạt DNS hostname và tạo VPC Endpoints (ssm, ssmmessages, ec2messages) <br>&emsp; + Khởi tạo EC2 Private và cấu hình IAM Role <br>&emsp; + Tạo S3 Gateway Endpoint và S3 Bucket cho session logs <br>&emsp; + Sử dụng Session Manager để truy cập EC2 và Port Forwarding | 23/10/2025   | 24/10/2025      | <https://000058.awsstudygroup.com/vi/> |


### Kết quả đạt được tuần 7:
* Amazon CloudWatch và Grafana
 * Thiết lập hệ thống giám sát tập trung bằng Grafana, tích hợp dữ liệu từ CloudWatch để phân tích hoạt động hệ thống.
* Tag và Resource Groups
 * Nắm vững kỹ năng tổ chức tài nguyên AWS thông qua Tag, sử dụng Resource Groups để quản lý hiệu quả và tối ưu bảo mật.
* AWS Systems Manager – Patch Manager
 * Thành thạo công cụ tự động hóa quản lý bản vá và vận hành hệ thống Windows, đảm bảo tính bảo mật và ổn định.
* AWS Systems Manager – Session Manager
 * Truy cập và quản lý máy chủ Private Network mà không cần SSH/RDP, tăng cường bảo mật và quản trị tập trung trên AWS.
