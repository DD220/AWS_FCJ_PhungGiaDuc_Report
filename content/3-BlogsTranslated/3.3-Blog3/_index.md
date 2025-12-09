---
title: "Blog 3"

weight: 1
chapter: false
pre: " <b> 3.3. </b> "
---

# AWS Transform for .NET Now Supports Q&A for Assessment and Transformation Reports  
**Authors:** David Pallmann, Vijay Mandadi, Rakshith Ravi Kumar  
**Published:** July 1, 2025  
**Categories:** .NET, AWS Transform  

---

## Introduction

AWS Transform for .NET accelerates large-scale modernization of .NET applications, including migrating from .NET Framework to cross-platform .NET and upgrading between .NET versions.  

Today, we are introducing a new **chat-based Q&A feature** that allows you to obtain insights about your transformation jobs directly from the **web console** using natural language.

This new capability lets you ask questions about assessment reports and transformation reports without manually browsing through long documents—especially useful when working with multiple repositories.

*(Note: The chat feature is currently available only in the web console, not in IDE integrations.)*

---

## Assessment Queries

When you configure a .NET transformation job, AWS Transform first evaluates the selected repositories.  
You can download the **assessment report** in HTML or JSON format from the **Collaboration** tab.

The assessment report provides details such as:

- Repository owner  
- Branch evaluated  
- Number of solutions  
- Number of projects  
- Total lines of code  
- Detected .NET versions  
- Project types  
- Public/private NuGet dependencies  
- Migration complexity  

Once the assessment is ready, the **Worklog** tab will display the message:  
**“Assessment report is now available in chat for queries.”**

To open the chat panel, click the purple hexagon icon at the bottom-right corner of the console.

### Example Assessment Queries:


The chat interface will interpret the assessment report and respond accordingly.

---

## Transformation Queries

After the transformation of a repository is completed—or when the entire job finishes—AWS Transform generates a **transformation report**.

The **Dashboard** tab displays the status of each repository:

- **In-progress**  
- **Success**  
- **Failed**  

You may download the transformation report or query it directly via chat.

### Example Transformation Queries:


Example:

- Asking **“What changes were made to the hello-bedrock repository?”** returns details on the migration from .NET 6 to .NET 8, Bedrock SDK updates, project structure improvements, and migration-analysis changes. The response also confirms that the transformation succeeded.

- Asking **“What packages were upgraded in the mathcore-main project?”** lists package upgrades such as NUnit, FluentAssertions, and Microsoft.NET.Test.Sdk.

---

## Providing Feedback

If the chat feature is unable to interpret your query, you may receive a generic fallback response.  
To improve accuracy:

- Clarify whether your question pertains to the **assessment report** or the **transformation report**  
- Review the downloaded reports to better understand their structure  

You can help AWS refine this capability by using the **thumbs up / thumbs down** icons under each chat response.  
Selecting one will open a prompt for additional feedback—greatly appreciated by AWS.

---

## Conclusion

This article demonstrates how to use AWS Transform for .NET’s natural language chat feature to explore:

- Repository assessment reports  
- Transformation reports  

The chat interface streamlines understanding of complex modernization workflows, enabling faster and more efficient .NET application upgrades.

---

## About the Authors

### **David Pallmann**  
Senior Product Manager on the AWS Transform team, specializing in the .NET developer experience.  
Former engineer, consultant, product manager, and engineering manager.  
Previously worked on WCF and created **Neuron ESB**, the first .NET-based enterprise service bus.  
Follow on X: **@davidpallmann**

---

### **Vijay Mandadi**  
Experienced technical leader in AWS Migrations and Modernizations with over 16 years of expertise across distributed systems, cloud computing, virtualization, workload transformation, and healthcare.  
At AWS, he focuses on leveraging **Generative AI** and **Agentic AI** to accelerate customer modernization efforts and enable cloud-native architectures.

---

### **Rakshith Ravi Kumar**  
Senior Software Engineer at AWS with more than 11 years of experience in software development.  
Expertise includes mobile development, CRM systems, NetBackup solutions, and cloud migration technologies.  
Currently working on **agentic solutions** for modernization and migration workloads.

---
