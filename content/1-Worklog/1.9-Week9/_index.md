---
title: "Week 9 Worklog"

date: 2025-11-01
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---


### Week 9 Objectives:

* Master AWS KMS and encryption key lifecycle management.
* Deploy and operate automated backup workflows using AWS Backup.
* Research, configure, and establish connectivity between VPCs using AWS Transit Gateway.
* Get familiar with Docker and deploy containerized applications on Amazon ECS.


### Tasks to be completed this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | ----- | ------------ | --------------- | ------------------ |
| 3   | - AWS KMS – **Hands-on:** <br>&emsp; + Create policy and role, configure sample groups and users <br>&emsp; + Create a CMK (Customer Master Key) and test encrypt/decrypt operations on S3 objects <br>&emsp; + Enable CloudTrail logging and query logs using Athena | 11/03/2025   | 11/03/2025      | 1. https://000033.awsstudygroup.com/en/ <br> 2. https://000013.awsstudygroup.com/en/ |
| 4   | - AWS Backup – **Hands-on:** <br>&emsp; + Prepare S3/resources templates and CloudFormation stack for backup <br>&emsp; + Configure Backup Plan, Backup Vault, and SNS notifications <br>&emsp; + Test restore to validate data availability | 11/04/2025   | 11/04/2025      | 1. https://000013.awsstudygroup.com/en/ <br> 2. https://000019.awsstudygroup.com/en/ |
| 5   | - Transit Gateway – **Hands-on:** <br>&emsp; + Create KeyPair and prepare CloudFormation template <br>&emsp; + Deploy Transit Gateway, create attachments and route tables <br>&emsp; + Add routes to VPC route tables and verify network connectivity | 11/05/2025   | 11/05/2025      | 1. https://000020.awsstudygroup.com/en/ <br> 2. https://000015.awsstudygroup.com/en/ |
| 6   | - Docker & Amazon ECS – Application Deployment: <br>&emsp; + Build Docker image for demo application <br>&emsp; + Push image to ECR <br>&emsp; + Create task definition and ECS service to run the container | 11/06/2025   | 11/06/2025      | 1. https://000016.awsstudygroup.com/en/ <br> 2. https://000015.awsstudygroup.com/en/ |


### Week 9 Achievements:
* Successfully configured and tested AWS WAF; collected request logs for analysis.
* Created and managed CMK, applied S3 object encryption, monitored activity using CloudTrail, and analyzed logs with Athena.
* Set up a complete AWS Backup environment including Backup Plan, Backup Vault, SNS notifications, and validated successful restore operations.
* Deployed Transit Gateway, enabling communication between multiple VPCs with proper routing verification.
* Gained understanding of Docker packaging and deployed containerized applications on ECS; familiarized with ECS task/service architecture.

