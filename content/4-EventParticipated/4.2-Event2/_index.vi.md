---
title: "Event 2"

weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---


# AWS Cloud Mastery Series #2

## Event Objectives
- Hiểu rõ nền tảng văn hóa DevOps và cách áp dụng trong doanh nghiệp  
- Nắm quy trình xây dựng CI/CD Pipeline bằng dịch vụ DevOps của AWS  
- Thực hành Infrastructure as Code (IaC) với CloudFormation & CDK  
- Khám phá container, theo dõi hệ thống và quan sát hiệu năng (observability)  

---

## Key Highlights

### 1. Tư duy DevOps & Nền tảng văn hóa
Buổi học mở đầu bằng việc nhắc lại nội dung AI/ML trước đó và đi vào trọng tâm:

- Tăng cường giao tiếp giữa các nhóm kỹ thuật  
- Tối ưu tốc độ phát triển qua tự động hóa và phản hồi nhanh  
- Giới thiệu các thước đo DevOps quan trọng: DORA metrics, MTTR, tần suất deploy  
- Nhấn mạnh vai trò của DevOps trong việc xây dựng hệ thống bền vững, linh hoạt  

---

### 2. AWS DevOps Services – Xây dựng CI/CD Pipeline

Toàn bộ quy trình DevOps-native trên AWS được hệ thống hóa:

**Quản lý mã nguồn**  
- AWS CodeCommit, GitFlow, và Trunk-based development  

**Build & Test**  
- Tạo cấu hình build với CodeBuild  
- Tự động chạy unit test / integration test trong pipeline  

**Triển khai (Deployment)**  
- CodeDeploy với chiến lược Blue/Green  
- Rolling & Canary deployments để giảm rủi ro khi đưa lên production  

**Orchestrator**  
- CodePipeline để gom toàn bộ quy trình CI/CD vào một luồng tự động hóa duy nhất  

**Live Demo**  
- Mô phỏng pipeline hoàn chỉnh từ commit → build → deploy  

---

### 3. Infrastructure as Code (IaC)

Nội dung chuyên sâu:

#### AWS CloudFormation  
- Khai báo hạ tầng bằng template  
- Deploy, quản lý stack và xử lý drift  

#### AWS CDK  
- Xây dựng tài nguyên AWS bằng code  
- Tái sử dụng cấu trúc thiết kế, hỗ trợ nhiều ngôn ngữ (Python, TS, Java…)  
- So sánh khi nào nên dùng CDK và khi nào nên dùng CloudFormation  

**Live Demo**  
- Tạo hạ tầng bằng cả CloudFormation và CDK  

---

## Key Takeaways

### DevOps Mindset  
- Ưu tiên tự động hóa để giảm lỗi thủ công  
- Liên tục triển khai và chia nhỏ release  
- Quyết định dựa trên số liệu đo đạc (DORA, MTTR)  

### Technical Architecture  
- Thiết kế CI/CD Pipeline linh hoạt và dễ mở rộng  
- IaC giúp đảm bảo tính nhất quán, giảm sai lệch cấu hình  
- Chọn dịch vụ container phù hợp: ECS, EKS hoặc App Runner  
- Observability là yếu tố trọng tâm trong vận hành  

### Modernization Strategy  
- Đưa ứng dụng sang microservices + container  
- Chuẩn hóa hạ tầng qua IaC ở mọi môi trường  
- Dùng blue/green & canary để tăng độ an toàn
- Tăng cường giám sát bằng CloudWatch và X-Ray  

### Applying to Work  
- Tạo CI/CD Pipeline với CodePipeline + CodeBuild + CodeDeploy  
- Triển khai IaC thay cho cấu hình thủ công  
- Container hóa workload, so sánh ECS/EKS/App Runner  
- Áp dụng best practice DevOps: A/B test, rollback tự động  

---

## Event Experience

### Học hỏi từ chuyên gia AWS  
- Hiểu về hành trình DevOps của nhiều doanh nghiệp  
- Nắm rõ lý do CI/CD giúp tăng tốc phát triển và giảm downtime  

### Trải nghiệm kỹ thuật trực tiếp  
- Đi sâu vào từng bước của CI/CD pipeline  
- Thực hành IaC qua CloudFormation & CDK  
- Demo container và observability từ đầu đến cuối  

### Công cụ hiện đại  
- Docker & ECR cho quy trình container  
- Bộ công cụ theo dõi hệ thống từ CloudWatch đến X-Ray  

### Thực tiễn & ví dụ thực tế  
- Các tình huống sự cố và quy trình postmortem  
- Tư duy triển khai an toàn bằng feature flag  
- Cách các doanh nghiệp vận hành DevOps ở quy mô lớn  

---

## Lessons Learned
- DevOps là văn hóa + tự động hóa, không chỉ là bộ công cụ  
- IaC là chìa khóa cho tốc độ và độ chính xác của hạ tầng  
- Containers + CI/CD giúp tăng tốc độ release đáng kể  
- Observability đóng vai trò sống còn trong hệ thống lớn