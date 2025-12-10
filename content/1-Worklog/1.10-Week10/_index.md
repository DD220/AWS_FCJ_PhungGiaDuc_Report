---
title: "Week 10 Worklog"
date: 2025-11-07
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Build a CI/CD pipeline using AWS CodePipeline/CodeBuild.
* Optimize configuration and cost efficiency for Amazon EC2.
* Visualize and analyze AWS cost usage.
* Deploy containerized applications on AWS.
* Design and test a Data Lake on AWS.

### Tasks to be completed this week:
| Day | Task | Date | Reference Material |
| --- | ----- | --------------- | ------------------ |
| 2   | - EC2 Optimization – **Hands-on:** <br>&emsp; + Monitor EC2 metrics in CloudWatch <br>&emsp; + Create IAM Role for CloudWatch Agent <br>&emsp; + Collect optimization data and apply recommendations from Compute Optimizer <br>&emsp; + Resize/reconfigure EC2 instance type accordingly | 10/11/2025     |  https://000032.awsstudygroup.com/en/ <br>  https://000040.awsstudygroup.com/en/ |
| 3   | - AWS CodePipeline & CI/CD – **Hands-on:** <br>&emsp; + Create repository and push sample source code <br>&emsp; + Configure CodeBuild and integrate GitHub (Actions/Access Key) <br>&emsp; + Set up CodePipeline to deploy to ECS <br>&emsp; + Route logs using FireLens, store logs in S3, and monitor via CloudWatch | 11/11/2025     | <https://000017.awsstudygroup.com/en/> |
| 4   | - Deploy Docker Application on AWS – **Hands-on:** <br>&emsp; + Install dependencies to run the application locally <br>&emsp; + Prepare VPC, Security Group, IAM Roles; authenticate Docker Hub/ECR <br>&emsp; + Prepare RDS and DB Subnet Group <br>&emsp; + Configure Ubuntu EC2 and deploy backend/frontend using Docker/Docker Compose | 12/11/2025    |  https://000024.awsstudygroup.com/en/ <br>  https://000015.awsstudygroup.com/en/ |
| 5   | - AWS Cost Visualization – **Hands-on:** <br>&emsp; + Analyze cost by service and account <br>&emsp; + Check Saving Plans coverage <br>&emsp; + Generate reports and charts via Cost Explorer <br>&emsp; + Export EC2 usage reports and analyze Data Transfer Out | 13/11/2025    | https://000034.awsstudygroup.com/en/ <br>  https://000032.awsstudygroup.com/en/ |
| 6   | - Build Data Lake on AWS – **Hands-on:** <br>&emsp; + Create IAM Role & policy for data ingestion <br>&emsp; + Create S3 Bucket for the data lake <br>&emsp; + Use Kinesis Firehose for ingestion <br>&emsp; + Create Glue Crawler/Catalog and inspect data on S3 <br>&emsp; + Analyze using Athena and visualize via QuickSight | 14/11/2025     | <https://000035.awsstudygroup.com/en/> |

### Week 10 Achievements:
* EC2 optimization: deployed CloudWatch Agent, collected performance metrics, applied Compute Optimizer recommendations, and resized instances effectively.
* Completed Data Lake design: ingested data via Kinesis Firehose, stored in S3, cataloged with Glue, analyzed using Athena, and created visualizations using QuickSight.
* Successfully deployed Docker-based applications on AWS: prepared infrastructure (VPC, SG, IAM), configured EC2, ran applications using Docker/Docker Compose, and pushed images to Docker Hub/ECR.
* Completed AWS cost analysis and visualization: service-level and account-level cost breakdown, Cost Explorer charts, Saving Plans evaluation, and Data Transfer Out analysis.
* Built CI/CD pipeline: configured CodeBuild/CodePipeline, integrated GitHub, routed logs with FireLens, stored logs to S3, and monitored with CloudWatch.
