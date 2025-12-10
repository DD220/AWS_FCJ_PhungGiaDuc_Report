---
title: "Event 2"

weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---


# AWS Cloud Mastery Series #2

## Event Objectives
- Understand the DevOps cultural foundation and how to apply it in enterprises  
- Master the process of building CI/CD pipelines using AWS DevOps services  
- Practice Infrastructure as Code (IaC) with CloudFormation & CDK  
- Explore containerization, system monitoring, and performance observability  

---

## Key Highlights

### 1. DevOps Mindset & Cultural Foundation
The session began with a brief recap of the previous AI/ML content and then moved into the main topics:

- Strengthening communication between technical teams  
- Improving development speed using automation and fast feedback loops  
- Introducing key DevOps metrics: DORA metrics, MTTR, deployment frequency  
- Highlighting the importance of DevOps in building scalable and resilient systems  

---

### 2. AWS DevOps Services – Building a CI/CD Pipeline

A complete DevOps-native workflow on AWS was presented:

**Source Control**  
- AWS CodeCommit, GitFlow, and Trunk-based development  

**Build & Test**  
- Creating build specifications using CodeBuild  
- Automatically running unit tests / integration tests within the pipeline  

**Deployment**  
- CodeDeploy with Blue/Green strategies  
- Rolling & Canary deployments to reduce production deployment risks  

**Orchestration**  
- CodePipeline to bring all CI/CD stages together into one automated flow  

**Live Demo**  
- Demonstrating a full pipeline from commit → build → deploy  

---

### 3. Infrastructure as Code (IaC)

Deep-dive topics included:

#### AWS CloudFormation  
- Declaring infrastructure using templates  
- Deploying, managing stacks, and handling drift  

#### AWS CDK  
- Defining AWS resources using code  
- Reusing architectural patterns with multi-language support (Python, TS, Java…)  
- Comparison: When to choose CDK vs CloudFormation  

**Live Demo**  
- Deploying infrastructure with both CloudFormation and CDK  

---

## Key Takeaways

### DevOps Mindset  
- Prioritize automation to reduce manual errors  
- Deploy continuously with smaller, safer releases  
- Make decisions based on measurable metrics (DORA, MTTR)  

### Technical Architecture  
- Build flexible and scalable CI/CD pipelines  
- IaC ensures consistency and minimizes configuration drift  
- Choose appropriate container services: ECS, EKS, or App Runner  
- Observability is a core component of system operations  

### Modernization Strategy  
- Migrate applications to microservices + containers  
- Standardize infrastructure across environments using IaC  
- Use blue/green & canary strategies for safer deployments  
- Strengthen monitoring with CloudWatch and X-Ray  

### Applying to Work  
- Build CI/CD pipelines with CodePipeline + CodeBuild + CodeDeploy  
- Replace manual configurations using IaC  
- Containerize workloads and evaluate ECS/EKS/App Runner  
- Apply DevOps best practices: A/B testing, automatic rollback  

---

## Event Experience

### Learning from AWS Experts  
- Understand DevOps journeys from real enterprises  
- Gain clarity on how CI/CD accelerates development while reducing downtime  

### Hands-on Technical Experience  
- Detailed walkthrough of each CI/CD pipeline stage  
- Practiced IaC using CloudFormation & CDK  
- Full demo of containerization and observability  

### Modern Tools  
- Docker & ECR for container workflows  
- Monitoring stack from CloudWatch to X-Ray  

### Practical Insights  
- Real incident scenarios and postmortem processes  
- Safe deployment techniques using feature flags  
- How large organizations operate DevOps at scale  

---

## Lessons Learned
- DevOps is culture + automation, not just tooling  
- IaC is the key to speed and accuracy in infrastructure management  
- Containers + CI/CD dramatically accelerate release cycles  
- Observability is critical for maintaining large-scale systems  
