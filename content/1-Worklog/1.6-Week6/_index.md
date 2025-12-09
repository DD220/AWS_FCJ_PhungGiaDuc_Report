---
title: "Week 6 Worklog"
date: 2025-10-13
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---


### Week 6 Objectives:

* Build highly available web applications (High Availability).
* Practice Amazon Route53 for DNS management.
* Use AWS CLI to manage resources on EC2.
* Develop and deploy AWS Lambda functions.
* Migrate and transfer virtual machines from on-premises to AWS.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Amazon Route53 - **Hands-on:** <br>&emsp; + Create KeyPair for secure connections <br>&emsp; + Build CloudFormation Template for automation <br>&emsp; + Configure Security Group to control traffic <br>&emsp; + Connect via RDGW using RDP and log in to server <br>&emsp; + Deploy Microsoft Active Directory (AD) <br>&emsp; + Set up Outbound Rules, Resolver Rules, Inbound Endpoints for DNS Resolution | 13/10/2025 | 13/10/2025      | <https://000010.awsstudygroup.com/en/> |
| 3   | - AWS CLI on EC2 - **Hands-on:** <br>&emsp; + Install AWS CLI on Linux <br>&emsp; + List and manage EC2 resources via CLI <br>&emsp; + Use CLI to interact with S3, SNS <br>&emsp; + Create and manage IAM identities <br>&emsp; + Initialize VPC, Internet Gateway, EC2 Instance entirely via command line | 14/10/2025 | 14/10/2025      | <https://000011.awsstudygroup.com/en/> |
| 4   | - AWS VM Import/Export - **Hands-on:** <br>&emsp; + Set up VMware Workstation to manage virtual machines <br>&emsp; + Successfully migrate VM from on-premises to AWS <br>&emsp; + Create EC2 Instance from imported AMI <br>&emsp; + Configure S3 Bucket ACL for access management <br>&emsp; + Export VM from EC2 Instance/AMI back to local machine | 16/10/2025 | 16/10/2025      | <https://000014.awsstudygroup.com/en/> |
| 5   | - AWS Lambda - **Hands-on:** <br>&emsp; + Prepare VPC, Security Group, EC2 Instance <br>&emsp; + Integrate Slack Webhook for enhanced monitoring <br>&emsp; + Tag instances <br>&emsp; + Create IAM Role for Lambda <br>&emsp; + Develop Lambda functions (Start/Stop) to automatically control EC2 <br>&emsp; + Verify operation and clean up resources | 17/10/2025 | 17/10/2025      | <https://000022.awsstudygroup.com/en/> |
| 6   | - Highly Available Web Application Workshop - **Hands-on:** <br>&emsp; + Prepare Security Group for EC2 and Database <br>&emsp; + Launch EC2 and RDS Database <br>&emsp; + Install WordPress on EC2 <br>&emsp; + Build Auto Scaling including: AMI, Launch Template, Target Group, Load Balancer, Auto Scaling Group <br>&emsp; + Snapshot Database and perform Recovery <br>&emsp; + Integrate CloudFront for acceleration | 15/10/2025 | 15/10/2025      | <https://000021.awsstudygroup.com/en/> |


### Week 6 Achievements:
* Amazon Route53
 * Successfully created KeyPair, CloudFormation Template, and Security Group for network architecture.
 * Set up remote connections via RDGW/RDP and accessed servers.
 * Deployed Microsoft Active Directory and configured DNS components (Outbound/Inbound Endpoints, Resolver Rules) in Route53.
* AWS CLI on EC2
 * Installed AWS CLI on Linux and practiced commands for managing EC2, S3, SNS, IAM, VPC.
 * Mastered automation to create Internet Gateway and EC2 Instance via CLI.
* Highly Available Web Application Workshop
 * Built WordPress web application with High Availability architecture including Auto Scaling, Load Balancer, CloudFront.
 * Configured AMI, Launch Template, Target Group to support automatic scaling based on demand.
 * Practiced Database Snapshot and Recovery; managed resources efficiently.
* AWS VM Import/Export
 * Successfully migrated VMware Workstation virtual machine to AWS EC2 Instance.
 * Configured S3 Bucket ACL and practiced exporting VM back to local machine; understood hybrid migration process.
* AWS Lambda
 * Created Lambda functions (Start/Stop) to automatically manage EC2 instance state; integrated Slack Webhook for monitoring.
 * Verified successful operation and cleaned up resources after completing the lab.