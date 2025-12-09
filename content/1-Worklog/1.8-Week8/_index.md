---
title: "Week 8 Worklog"

date: 2025-10-27
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---


### Week 8 Objectives:

* Practice configuring Amazon SSO (IAM Identity Center) for a multi-account environment.
* Become familiar with and deploy resources using Amazon CloudFormation.
* Apply IAM Permission Boundaries to limit identity permissions.
* Practice creating IAM Roles with Conditions to refine access restrictions.
* Enable and use AWS Security Hub for security posture assessments.
* Configure AWS WAF to protect web applications from common attacks.


### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - IAM Role & Condition - **Hands-on:** <br>&emsp; + Create sample IAM Roles and IAM Users <br>&emsp; + Inspect and analyze permissions of created identities <br>&emsp; + Create an Admin Role and try Switch Role <br>&emsp; + Apply Conditions to restrict access by IP and by time window | 10/28/2025 | 10/28/2025      | <https://000044.awsstudygroup.com/en/> <https://000018.awsstudygroup.com/en/> |
| 3   | - Amazon SSO (Identity Center) - **Hands-on:** <br>&emsp; + Use AWS Organizations to create/manage AWS Accounts <br>&emsp; + Configure IAM Identity Center and create Users/Groups <br>&emsp; + Create Permission Sets, assign to accounts and verify access with time-based controls <br>&emsp; + Practice customer managed policies and Identity Store APIs | 10/29/2025 | 10/29/2025      | <https://000030.awsstudygroup.com/en/> |
| 4   | - Amazon CloudFormation - **Hands-on:** <br>&emsp; + Prepare IAM Roles and Users for deployment <br>&emsp; + Create a workspace and author templates on Cloud9 <br>&emsp; + Deploy a Lambda function, create a Stack and connect EC2 resources <br>&emsp; + Use StackSets for multi-region deployments and run Drift Detection | 10/30/2025 | 10/30/2025      | <https://000037.awsstudygroup.com/en/> |
| 5   | - IAM Permission Boundary & AWS WAF - **Hands-on:** <br>&emsp; + Create a Permission Boundary policy and apply it to an IAM User <br>&emsp; + Observe the behavior of a permission-limited user <br>&emsp; + Create an S3 bucket and host a sample web page <br>&emsp; + Configure Web ACLs with managed rules and a custom rule; test the rule and log requests via WAF | 10/31/2025 | 10/31/2025      | <> |


### Week 8 Achievements:
* Prepared tooling and documentation environment
 * Installed and configured supporting tools: Hugo theme, Snagit, ActivePresenter, and Draw.io for note-taking, recording, and architecture diagrams.
 * Set up a ready practice environment for writing guides and reports.
* IAM Role & Conditions – AWS Security Hub
 * Gained experience creating, managing, and constraining IAM permissions; used AWS Security Hub to assess compliance against AWS Foundational Security Best Practices.
* Amazon SSO – IAM Identity Center
 * Deployed an SSO model across multiple AWS accounts, managed users and permission sets, including time-based access controls.
* Amazon CloudFormation
 * Practiced automating infrastructure deployment with CloudFormation, managed multi-region deployments with StackSets, and tracked drift.
* IAM Permission Boundary & AWS WAF
 * Applied Permission Boundaries to limit identity scopes; configured AWS WAF (Web ACLs, managed rules, and custom rules) to protect web applications and logged requests for analysis.
