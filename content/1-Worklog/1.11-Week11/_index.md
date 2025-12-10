---
title: "Week 11 Worklog"
date: 2025-11-13
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11 Objectives:

* Understand Serverless architecture and its implementation on AWS.
* Master the process of building APIs and Frontend applications using a serverless model.
* Become familiar with AWS SAM for Infrastructure as Code (IaC) deployments.
* Develop, deploy, and automate Microservices on AWS.
* Improve data organization and workflow optimization within Microservices.
* Explore Messaging & Eventing mechanisms in distributed Microservice architectures.

### Tasks to be completed this week:
| Day | Task                                                                                                                                                                                   | Date | References |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | ----------------------------------------- |
| 2   | - Serverless – Lambda interacting with S3 & DynamoDB – **Hands-on:** <br>&emsp; + Create a Lambda function to process images uploaded to S3 <br>&emsp; + Create an S3 Bucket for storing images <br>&emsp; + Write an IAM Policy for the Lambda function <br>&emsp; + Validate the Lambda Function execution flow <br>&emsp; + Create a DynamoDB table for data management <br>&emsp; + Build a Lambda function to write data to DynamoDB <br><br> - Serverless Frontend & API Gateway – **Hands-on:** <br>&emsp; + Deploy a web frontend to an S3 Bucket <br>&emsp; + Create a DynamoDB table to store information <br>&emsp; + Build 3 Lambda functions for read/write/delete operations <br>&emsp; + Configure API Gateway methods & CORS <br>&emsp; + Test APIs using Postman and from the frontend | 17/11/2025  |  <https://000078.awsstudygroup.com/en/> <br>  https://000079.awsstudygroup.com/en/ |
| 3   | - Build a Microservice – **Hands-on:** <br>&emsp; + Create a CloudFormation Stack as the practice environment <br>&emsp; + Configure EC2 & Eclipse IDE <br>&emsp; + Initialize a Lambda project using AWS Toolkit <br>&emsp; + Upload Lambda function to AWS from Eclipse <br>&emsp; + Build an image-processing Lambda function & deploy via Console <br>&emsp; + Use Maven & PowerShell for automated microservice deployment <br>&emsp; + Create a source repository via AWS CodeStar <br>&emsp; + Integrate CI/CD pipeline and update API Target Region | 18/11/2025  |  <https://000052.awsstudygroup.com/en/>  |
| 4   | - Data restructuring & workflow optimization – **Hands-on:** <br>&emsp; + Create a new Key Pair & CloudFormation Stack <br>&emsp; + Launch and connect to a Windows Instance for development <br>&emsp; + Add a Global Secondary Index to the DynamoDB table <br>&emsp; + Create a new CodeStar repository & import project from Eclipse <br>&emsp; + Rebuild the Microservice project and update API Target Region <br>&emsp; + Add IAM Policy for the role <br>&emsp; + Deploy via AWS Pipeline <br>&emsp; + Upgrade TripSearch Microservice & add Step Functions workflow <br>&emsp; + Integrate Lambda into workflow & extend calculation logic <br>&emsp; + Download CalculatorStepFull.zip and import into Eclipse IDE | 19/11/2025  |  <https://000053.awsstudygroup.com/en/>  |
| 5   |   AWS SAM – writing templates, packaging, and deploying serverless applications with IaC | 20/11/2025 | https://000080.awsstudygroup.com/en/ |
| 6   |   Messaging & Eventing in Microservices – operating models, AWS services, and how to apply them in distributed architectures | 21/11/2025 | https://000054.awsstudygroup.com/en/ |

### Week 11 Achievements:
* Successfully built a Serverless system integrating Lambda – S3 – DynamoDB: image processing, IAM policy configuration, DynamoDB read/write operations, and direct validation via AWS Console.
* Developed a Serverless application combining API Gateway and Frontend: created 3 CRUD Lambda functions, fully configured CORS, tested APIs via Postman, and deployed the frontend to S3 for end-to-end validation.
* Gained solid understanding of AWS SAM operations: creating templates, packaging, and deploying stacks using Infrastructure as Code.
* Completed a full Microservice implementation: provisioning environment using CloudFormation, developing with AWS Toolkit in Eclipse, deploying through Maven/PowerShell, managing code with AWS CodeStar, integrating CI/CD, and configuring API Target Region.
* Reorganized Microservice workflows & data: added GSI for DynamoDB, optimized project source, redeployed via pipeline, expanded TripSearch Microservice, created Step Functions workflows, integrated Lambda functions, and enhanced processing logic.
* Explored concepts of Microservice Messaging & Eventing and learned how to apply event-driven patterns across AWS distributed systems.
