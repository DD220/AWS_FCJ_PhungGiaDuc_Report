---
title: "Worklog Tuần 10"
date: 2025-11-07
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Mục tiêu tuần 10:

* Xây dựng pipeline CI/CD với AWS CodePipeline/CodeBuild.
* Tối ưu hoá cấu hình và chi phí của Amazon EC2.
* Trực quan hóa và phân tích chi phí AWS.
* Triển khai ứng dụng container trên AWS.
* Thiết kế và thử nghiệm Data Lake trên AWS.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tối ưu hoá tài nguyên EC2 - **Thực hành:** <br>&emsp; + Kiểm tra metric trên CloudWatch <br>&emsp; + Tạo IAM Role cho CloudWatch Agent <br>&emsp; + Thu thập dữ liệu tối ưu hoá và áp dụng đề xuất từ Compute Optimizer <br>&emsp; + Cấu hình lại size/instance type hợp lý | 08/11/2025   | 08/11/2025      | 1. https://000032.awsstudygroup.com/en/ <br> 2. https://000040.awsstudygroup.com/en/ |
| 3   | - AWS CodePipeline & CI/CD - **Thực hành:** <br>&emsp; + Tạo repository và push mã nguồn mẫu <br>&emsp; + Cấu hình CodeBuild và tích hợp GitHub (Actions/Access Key) <br>&emsp; + Thiết lập CodePipeline để deploy lên ECS <br>&emsp; + Chuyển hướng logs bằng FireLens, lưu trữ logs trên S3 và theo dõi bằng CloudWatch | 11/11/2025   | 11/11/2025      | <https://000017.awsstudygroup.com/en/> |
| 4   | - Triển khai ứng dụng Docker lên AWS - **Thực hành:** <br>&emsp; + Cài đặt phụ thuộc chạy ứng dụng ở local <br>&emsp; + Chuẩn bị VPC, Security Group, IAM Roles; đăng nhập Docker Hub/ECR <br>&emsp; + Chuẩn bị RDS và DB Subnet Group <br>&emsp; + Cấu hình EC2 Ubuntu và chạy Docker/Docker Compose cho backend/frontend | 10/11/2025   | 10/11/2025      | 1. https://000024.awsstudygroup.com/vi/ <br> 2. https://000015.awsstudygroup.com/en/ |
| 5   | - Trực quan hóa chi phí AWS - **Thực hành:** <br>&emsp; + Phân tích chi phí theo dịch vụ và tài khoản <br>&emsp; + Kiểm tra phạm vi áp dụng của Saving Plans <br>&emsp; + Tạo báo cáo và biểu đồ bằng Cost Explorer <br>&emsp; + Xuất báo cáo sử dụng EC2 và phân tích Data Transfer Out | 07/11/2025   | 07/11/2025      | 1. https://000034.awsstudygroup.com/en/ <br> 2. https://000032.awsstudygroup.com/en/ |
| 6   | - Xây dựng Data Lake trên AWS - **Thực hành:** <br>&emsp; + Tạo IAM Role & policy cho ingestion <br>&emsp; + Tạo S3 Bucket làm data lake <br>&emsp; + Dùng Kinesis Firehose để ingest dữ liệu <br>&emsp; + Tạo Glue Crawler/Catalog và kiểm tra dữ liệu trên S3 <br>&emsp; + Phân tích bằng Athena và trực quan hóa bằng QuickSight | 12/11/2025   | 12/11/2025      | <https://000035.awsstudygroup.com/en/> |

### Kết quả đạt được tuần 10:
* Tối ưu hóa EC2: triển khai CloudWatch Agent, thu thập metric, áp dụng khuyến nghị từ Compute Optimizer và điều chỉnh kích thước instance phù hợp.
* Hoàn thiện Data Lake: ingestion bằng Kinesis Firehose, lưu trên S3, catalog bằng Glue, phân tích bằng Athena và trực quan hóa bằng QuickSight.
* Triển khai ứng dụng Docker trên AWS: chuẩn bị hạ tầng (VPC, SG, IAM), cấu hình EC2, chạy ứng dụng bằng Docker/Docker Compose, và đẩy image lên Docker Hub/ECR.
* Hoàn thành phân tích và trực quan hóa chi phí AWS: báo cáo theo dịch vụ, theo tài khoản, biểu đồ Cost Explorer và đánh giá Saving Plans; xác định chi phí Data Transfer Out.
* Xây dựng CI/CD: cấu hình CodeBuild/CodePipeline, tích hợp GitHub, định tuyến logs qua FireLens và lưu logs trên S3, theo dõi bằng CloudWatch.
