---
title: "Worklog Tuần 8"

date: 2025-10-27
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---


### Mục tiêu tuần 8:

* Thực hành cấu hình Amazon SSO (IAM Identity Center) cho môi trường nhiều tài khoản.
* Làm quen và triển khai tài nguyên bằng Amazon CloudFormation.
* Áp dụng IAM Permission Boundaries để giới hạn phạm vi quyền cho identities.
* Thực hành tạo IAM Role với điều kiện (Condition) để tinh chỉnh ràng buộc truy cập.
* Kích hoạt và sử dụng AWS Security Hub để đánh giá an ninh.
* Thiết lập AWS WAF để bảo vệ ứng dụng web khỏi các tấn công phổ biến.


### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - IAM Role & Condition - **Thực hành:** <br>&emsp; + Tạo IAM Role và IAM User mẫu <br>&emsp; + Kiểm tra, phân tích quyền của IAM identities đã tạo <br>&emsp; + Tạo IAM Admin Role và thử Switch Role <br>&emsp; + Áp dụng điều kiện giới hạn truy cập theo IP và theo khung giờ | 28/10/2025   | 28/10/2025      | <https://000044.awsstudygroup.com/vi/> <https://000018.awsstudygroup.com/vi/> |
| 3   | - Amazon SSO - **Thực hành:** <br>&emsp; + Sử dụng AWS Organizations để tạo và quản lý AWS Accounts <br>&emsp; + Cấu hình IAM Identity Center (SSO) và tạo Users/Groups <br>&emsp; + Tạo Permission Sets, gán vào tài khoản và kiểm tra quyền bằng Time-based access control <br>&emsp; + Thực hành Customer Managed Policies và Identity Store APIs | 29/10/2025   | 29/10/2025      | <https://000030.awsstudygroup.com/vi/> |
| 4   | - Amazon CloudFormation - **Thực hành:** <br>&emsp; + Chuẩn bị IAM Role và IAM User cho deployment <br>&emsp; + Tạo Workspace và soạn Template trên Cloud9 <br>&emsp; + Triển khai Lambda Function, tạo Stack, và kết nối tài nguyên EC2 <br>&emsp; + Sử dụng StackSets cho multi-region và áp dụng Drift Detection | 30/10/2025   | 30/10/2025       | <https://000037.awsstudygroup.com/vi/> |
| 5   | - IAM Permission Boundary & AWS WAF - **Thực hành:** <br>&emsp; + Tạo Policy làm giới hạn quyền (Permission Boundary) và áp dụng cho IAM User <br>&emsp; + Kiểm tra hành vi của IAM User bị giới hạn quyền <br>&emsp; + Tạo S3 Bucket và chạy thử web mẫu <br>&emsp; + Cấu hình Web ACLs với managed rules và tạo Custom Rule; kiểm thử rule và lưu logs các request bằng WAF | 31/10/2025   | 31/10/2025      | <> |


### Kết quả đạt được tuần 8:
* Chuẩn bị công cụ học tập và triển khai tài liệu
 * Cài đặt và cấu hình các công cụ hỗ trợ: Hugo Theme, Snagit, Active Presenter và Draw.io để phục vụ việc ghi chép, quay video và thiết kế sơ đồ kiến trúc.
 * Thiết lập môi trường thực hành sẵn sàng cho việc ghi tài liệu hướng dẫn và báo cáo.
* IAM Role & Condition – AWS Security Hub
 * Nắm vững cách tạo, quản lý và giới hạn quyền truy cập IAM nâng cao; sử dụng AWS Security Hub để đánh giá các tiêu chuẩn bảo mật (AWS Foundational Security Best Practices).
* Amazon SSO – IAM Identity Center
 * Triển khai mô hình SSO cho nhiều tài khoản AWS, quản lý người dùng và permission sets hiệu quả, bao gồm kiểm soát truy cập theo thời gian.
* Amazon CloudFormation
 * Thực hành tự động hóa triển khai hạ tầng bằng CloudFormation, quản lý multi-region với StackSets và theo dõi drift để đảm bảo tính nhất quán.
* IAM Permission Boundary & AWS WAF
 * Áp dụng Permission Boundaries để giới hạn phạm vi quyền cho identities; cấu hình AWS WAF (Web ACLs, managed rules, custom rules) để bảo vệ ứng dụng web và lưu logs để phân tích sự kiện.
