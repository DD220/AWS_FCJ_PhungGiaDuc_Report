---
title: "Blog 1"
weight: 1
chapter: false
pre: " <b> 3.1. </b> "
---

# Giải pháp Xử lý Khiếu nại DCA trong Ngành Tài chính Ô tô (Motor Finance) với Dịch vụ của AWS  
**Tác giả:** Kaushal Goyal, Dogus Gucsav, và Pardeep Kumar  
**Ngày đăng:** 27/06/2025  
**Danh mục:** Amazon AppFlow, Amazon Bedrock, Amazon CloudWatch, Amazon Connect, Amazon DynamoDB, Amazon Pinpoint, Amazon QuickSight, Amazon VPC, AWS CloudTrail, AWS Database Migration Service, AWS Glue, AWS IAM, AWS KMS, AWS Lambda, AWS Step Functions, Financial Services, Generative AI, Industries  

---

## Tổng quan  
Ngành Motor Finance tại Vương quốc Anh đang đối mặt với những thử thách phức tạp sau khi FCA xem xét Discretionary Commission Arrangements (DCA). Các tổ chức tài chính phải phân tích dữ liệu cũ, tính toán mức bồi thường chính xác, quản lý liên lạc khách hàng — trong khi dữ liệu phân mảnh và thời hạn pháp lý gấp rút.

Bài viết trình bày cách AWS hỗ trợ xây dựng một giải pháp có khả năng mở rộng để xử lý khiếu nại DCA và tạo nền tảng dữ liệu chiến lược cho nhu cầu tuân thủ trong tương lai.

---

## Thách thức chính
- Xử lý khối lượng lớn dữ liệu khách hàng lưu trữ trên nhiều hệ thống cũ khác nhau  
- Trích xuất thông tin từ tài liệu legacy và dữ liệu phi cấu trúc  
- Tính toán bồi thường theo quy tắc nghiệp vụ phức tạp  
- Quản lý yêu cầu qua nhiều kênh liên hệ  
- Đảm bảo tuân thủ GDPR và chuẩn pháp lý  
- Đáp ứng thời hạn xử lý chặt chẽ  

---

## Kiến trúc giải pháp  
Kiến trúc gồm **4 thành phần chính**, tạo thành một pipeline phân tích tài liệu và dữ liệu, tính toán bồi thường và quản lý giao tiếp khách hàng.

### 1. Intelligent Document Processing  
Sử dụng GenAI với Amazon Bedrock để phân tích hợp đồng tài chính, trích xuất:  
- APR gốc  
- Lãi suất hiệu dụng  
- Hoa hồng môi giới  
- Tài liệu bán hàng  

Tự động xác định khách hàng bị ảnh hưởng và mức độ có thể bị tính phí sai.  
Tài liệu được tải lên S3 qua AWS DataSync hoặc AWS Transfer Family.

---

### 2. Data Ingestion & Preparation  
- AWS DMS chuyển dữ liệu legacy sang AWS  
- Dữ liệu được lưu trong Amazon S3 làm data lake  
- AWS Glue crawler lập danh mục & enrich dữ liệu  
- AWS Glue jobs chuẩn hóa dữ liệu  
- Amazon AppFlow kết nối dữ liệu từ SaaS (Salesforce, SAP, ServiceNow, …)

PCB chuẩn hóa dữ liệu → chuẩn bị cho tính toán bồi thường.

---

### 3. Redress Calculation Engine  
Kiến trúc serverless dùng để tính toán mức bồi thường:

- AWS Lambda xử lý tính toán ở quy mô lớn  
- Amazon DynamoDB lưu quy tắc nghiệp vụ  
- AWS Step Functions điều phối workflow  
- Amazon QuickSight cung cấp dashboard theo dõi tiến độ & tác động tài chính  

Giải pháp tự động mở rộng khi lượng khiếu nại tăng và lưu trữ đầy đủ audit logs phục vụ FCA.

---

### 4. Customer Communication Hub  
- Amazon Connect làm contact center  
- Amazon Pinpoint gửi thông báo đa kênh  
- AWS Amplify triển khai các self-service portals  
- Amazon AppFlow tích hợp CRM như Salesforce  
- Amazon Q in QuickSight giúp phân tích dữ liệu bằng truy vấn ngôn ngữ tự nhiên

Giải pháp đảm bảo trải nghiệm khách hàng thống nhất và hỗ trợ xử lý lượng lớn yêu cầu từ FOS.

---

## Security & Compliance  
Giải pháp vận hành trong môi trường bảo mật cao:

- Amazon VPC để cô lập mạng  
- AWS KMS mã hóa dữ liệu nhạy cảm  
- AWS Secrets Manager quản lý bí mật  
- AWS IAM kiểm soát truy cập chi tiết  
- Amazon CloudWatch & AWS CloudTrail giám sát & kiểm toán  

Đáp ứng đầy đủ yêu cầu FCA và GDPR.

---

## Lợi ích & Kết luận  
Giải pháp AWS giúp các tổ chức tài chính:

- Xử lý nhanh khối lượng lớn khiếu nại DCA  
- Tuân thủ pháp lý  
- Cải thiện hiệu quả vận hành  
- Tạo nền tảng dữ liệu chiến lược phục vụ cho yêu cầu tương lai  

Kiến trúc serverless giúp tối ưu chi phí và tự động mở rộng. Managed services giảm đáng kể chi phí vận hành.

Các tổ chức nên đánh giá nhu cầu cụ thể để lựa chọn phương án triển khai phù hợp nhất.

Để tìm hiểu thêm, hãy liên hệ đội ngũ AWS hoặc đối tác Financial Services Competency.

---

## Tác giả

### **Kaushal Goyal**  
Solutions Architect tại AWS, phụ trách khách hàng Enterprise trong lĩnh vực Financial Services tại UK&I. Chuyên về hiện đại hóa hệ thống legacy và kiến trúc cloud-native. Đam mê Generative AI và công nghệ container.

### **Dogus Gucsav**  
Senior Solutions Architect tại AWS, chuyên các giải pháp cloud-native trong ngành tài chính. Hỗ trợ các ngân hàng nâng cao khả năng đổi mới với AI và kiến trúc composable banking.

### **Pardeep Kumar**  
Data Architect thuộc AWS Professional Services. Chuyên thiết kế nền tảng dữ liệu an toàn, mở rộng và ứng dụng AI tạo sinh nhằm tạo giá trị kinh doanh thực tế.

