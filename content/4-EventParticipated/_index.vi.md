# Summary Report: “AWS Well-Architected Framework – Security Pillar Workshop”

## Event Objectives
- Tìm hiểu chuyên sâu về Security Pillar trong AWS Well-Architected Framework  
- Nắm các nguyên tắc bảo mật hiện đại: Zero Trust, Least Privilege, Defense-in-Depth  
- Học cách thiết kế kiến trúc AWS an toàn từ IAM → Detection → Infrastructure → Data → Incident Response  

---

## Key Highlights

### 1. Security Foundation  
Buổi workshop mở đầu bằng phần giới thiệu về vai trò của Security Pillar:

- Xác định tầm quan trọng của Least Privilege  
- Áp dụng Zero Trust trong môi trường cloud  
- Bảo vệ nhiều lớp – Defense in Depth  
- Nhắc lại Shared Responsibility Model  
- Tổng hợp các rủi ro phổ biến tại Việt Nam (misconfiguration, stolen credentials, dữ liệu public ngoài ý muốn)  

---

### 2. Pillar 1 — Identity & Access Management (IAM)

#### Kiến trúc IAM hiện đại  
- Sử dụng IAM Roles & Policies thay vì long-lived credentials  
- IAM Identity Center cho quản lý truy cập tập trung  
- Multi-account governance với SCP & permission boundaries  
- Cách bảo vệ danh tính: MFA, key rotation, Access Analyzer  
- Mini demo: kiểm tra quyền bằng IAM Policy Simulator  

---

### 3. Pillar 2 — Detection

#### Giám sát & phát hiện liên tục  
- Thiết lập CloudTrail toàn tổ chức  
- GuardDuty để phát hiện hành vi bất thường  
- Security Hub tổng hợp toàn bộ cảnh báo  
- Thu thập log: VPC Flow Logs, ALB Logs, S3 Access Logs  
- EventBridge để tự động cảnh báo  
- Mô hình Detection-as-Code giúp tái sử dụng quy tắc giám sát  

---

### 4. Pillar 3 — Infrastructure Protection

#### Bảo vệ mạng & workload  
- Thiết kế VPC phân lớp, private vs public subnet  
- So sánh Security Groups và NACLs + best practices  
- Tường lửa nhiều lớp: WAF, Shield, Network Firewall  
- Bảo vệ workload trên EC2, ECS, EKS  

---

### 5. Pillar 4 — Data Protection

#### Mã hóa & quản lý dữ liệu  
- Sử dụng AWS KMS: key policy, grants, rotation  
- Best practice mã hóa cho S3 / EBS / RDS / DynamoDB  
- Quản lý secret bằng Secrets Manager & Parameter Store  
- Quy trình phân loại dữ liệu & thiết lập guardrails  

---

### 6. Pillar 5 — Incident Response

#### Quy trình ứng phó sự cố  
- Chu trình IR của AWS  
- Các playbook phổ biến:

  - Xử lý khóa IAM bị lộ  
  - Khắc phục S3 bucket bị public  
  - Ứng phó malware trên EC2  

- Kỹ thuật thu thập bằng chứng, snapshot, cô lập tài nguyên  
- Tự động hóa IR bằng Lambda và Step Functions  

---

## Wrap-Up & Q&A  
- Tổng hợp lại 5 Pillars
- Nêu các sai lầm phổ biến trong triển khai bảo mật ở Việt Nam  
- Lộ trình học tập đề xuất: Security Specialty, SA Pro  

---

## Key Takeaways

### Security Mindset  
- Bảo mật phải được thiết kế ngay từ đầu  
- Luôn áp dụng least privilege + identity hardening  
- Ghi log đầy đủ và giám sát liên tục  

### Technical Execution  
- Sử dụng IAM Identity Center cho quản lý tập trung  
- Duy trì hệ thống logging/threat detection toàn diện  
- Chia mạng theo lớp và áp dụng multi-layer defense  
- Mã hóa, rotate secrets và chuẩn hóa quản lý khóa  

### Operational Excellence  
- Xây dựng playbook xử lý sự cố  
- Tự động hóa phát hiện & khắc phục  
- Thiết lập governance cho multi-account AWS  

---

## Applying to Work  
- Rà soát IAM và chuyển sang mô hình IAM hiện đại  
- Áp dụng CloudTrail tổ chức + logging tập trung  
- Củng cố bảo mật hạ tầng với segmentation + WAF  
- Chuẩn hóa mã hóa, rotation và secret governance  
- Viết playbook sự cố và tự động hóa IR  

---

## Event Experience

### Học hỏi từ chuyên gia  
- Thảo luận các sự cố thực tế tại Việt Nam  
- Học các pattern bảo mật chuẩn AWS  

### Trải nghiệm thực hành  
- Demo IAM Policy Simulator  
- Thực hành phát hiện mối đe dọa và quy trình IR tự động  

### Tư duy chiến lược  
- Hiểu rằng bảo mật không chỉ là kỹ thuật mà còn là governance, quy trình và văn hóa  
- Nhìn rõ bức tranh bảo mật tổng thể của kiến trúc AWS  

### Cơ hội kết nối  
- Trao đổi với các chuyên gia và doanh nghiệp đang triển khai bảo mật cloud  

---

## Lessons Learned  
- Security là quá trình dài hạn  
- Logging + Monitoring là yếu tố bắt buộc  
- IAM hiện đại là nền móng của bảo mật cloud  
- Tự động hóa IR giúp giảm thiểu thiệt hại và tăng tốc ứng phó