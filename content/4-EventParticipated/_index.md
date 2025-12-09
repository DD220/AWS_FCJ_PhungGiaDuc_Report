# Summary Report: “AWS Well-Architected Framework – Security Pillar Workshop”

## Event Objectives
- Deep-dive into the Security Pillar of the AWS Well-Architected Framework  
- Understand modern security principles: Zero Trust, Least Privilege, Defense-in-Depth  
- Learn how to design secure AWS architectures from IAM → Detection → Infrastructure → Data → Incident Response  

---

## Key Highlights

### 1. Security Foundation  
The workshop began with an introduction to the importance of the Security Pillar:

- Emphasizing the role of Least Privilege  
- Applying Zero Trust in cloud environments  
- Multi-layer protection – Defense in Depth  
- Revisiting the Shared Responsibility Model  
- Overview of common risks in Vietnam (misconfigurations, stolen credentials, unintended public data exposure)  

---

### 2. Pillar 1 — Identity & Access Management (IAM)

#### Modern IAM Architecture  
- Prefer IAM Roles & Policies over long-lived credentials  
- IAM Identity Center for centralized access management  
- Multi-account governance with SCPs & permission boundaries  
- Identity hardening: MFA, key rotation, Access Analyzer  
- Mini demo: validating permissions with IAM Policy Simulator  

---

### 3. Pillar 2 — Detection

#### Continuous monitoring & threat detection  
- Organization-wide CloudTrail configuration  
- GuardDuty for anomaly detection  
- Security Hub for centralized alert aggregation  
- Logging sources: VPC Flow Logs, ALB Logs, S3 Access Logs  
- EventBridge for automated alerts  
- Detection-as-Code model for reusable detection rules  

---

### 4. Pillar 3 — Infrastructure Protection

#### Protecting network & workloads  
- Layered VPC design, private vs public subnets  
- SG vs NACLs comparison with best practices  
- Multi-layer firewalls: WAF, Shield, Network Firewall  
- Workload protection across EC2, ECS, EKS  

---

### 5. Pillar 4 — Data Protection

#### Data security & encryption  
- Using AWS KMS: key policies, grants, rotation  
- Best practices for encrypting S3 / EBS / RDS / DynamoDB  
- Managing secrets with Secrets Manager & Parameter Store  
- Data classification and guardrail design  

---

### 6. Pillar 5 — Incident Response

#### Incident Response workflows  
- AWS IR lifecycle  
- Common playbooks:

  - Handling leaked IAM credentials  
  - Fixing public S3 buckets  
  - Responding to malware on EC2  

- Evidence collection techniques: snapshots, isolation  
- Automating IR using Lambda and Step Functions  

---

## Wrap-Up & Q&A  
- Summary of all 5 Pillars  
- Discussion of common security pitfalls in Vietnam  
- Recommended learning path: Security Specialty, SA Pro  

---

## Key Takeaways

### Security Mindset  
- Security must be designed from the beginning  
- Always enforce least privilege + identity hardening  
- Logging and continuous monitoring are mandatory  

### Technical Execution  
- Use IAM Identity Center for centralized governance  
- Maintain comprehensive logging & threat detection  
- Apply network segmentation and multi-layer defense  
- Encrypt everything, rotate secrets, standardize key management  

### Operational Excellence  
- Build and maintain incident response playbooks  
- Automate detection and remediation  
- Establish proper governance for multi-account AWS  

---

## Applying to Work  
- Review IAM and transition to modern IAM practices  
- Enable organization-wide CloudTrail + centralized logging  
- Strengthen infrastructure security with segmentation + WAF  
- Standardize encryption, rotation, and secret governance  
- Write IR playbooks and automate the IR workflow  

---

## Event Experience

### Learning from experts  
- Discussing real security incidents in Vietnam  
- Understanding AWS best-practice security patterns  

### Hands-on experience  
- IAM Policy Simulator demo  
- Practical threat detection and automated IR scenarios  

### Strategic mindset  
- Recognizing that security involves governance, processes, and culture  
- Seeing the big picture of AWS security architecture  

### Networking opportunities  
- Engaging with experts and organizations implementing cloud security  

---

## Lessons Learned  
- Security is a long-term continuous process  
- Logging + Monitoring are non-negotiable  
- Modern IAM is the foundation of cloud security  
- Automated IR reduces impact and accelerates response  
