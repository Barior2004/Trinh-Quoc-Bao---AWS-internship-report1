---
title: "Week 4 Worklog"
.Date: "`r Sys..Date()`"
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---
### Week 4 Objectives:

* Understand the concept of VM Import/Export and why businesses need this feature.
* Learn how to import virtual machines (VMs) from on-premises environments to AWS and export them back when necessary.
* Get familiar with Amazon FSx for Windows File Server, understand its architecture, benefits, and real-world use cases.
* Practice creating, configuring, and managing an FSx File System.
* Enhance skills in using both AWS CLI and AWS Management Console to work with storage-related services.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start .Date | Completion .Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Learn about the concept of VM Import/Export in AWS. <br> - Understand the roles of S3 and IAM Role in the import/export process. <br> - Understand the purposes:: <br>&emsp; + Migrate virtual machines from on-premises to EC2. <br>&emsp; +  Use for backup or disaster recovery between local and cloud environments.                                                                                           | 28/09/2025   | 29/09/2025      | <https://000014.awsstudygroup.com/>
| 3   | - Prepare the environment for VM Import/Export. <br> - **Practice:** <br>&emsp; + Create an S3 bucket to store virtual machine files. <br>&emsp; + Configure IAM Role (vmimport) with necessary permissions. <br>&emsp; + Install AWS CLI and verify account credentials.                                           | 29/09/2025   | 30/09/2025      | <https://000014.awsstudygroup.com/> |
| 4   | - Practice importing a virtual machine to EC2. <br> - After finish, launch an instance from the created AMI. <br> - Practice exporting the EC2 instance back to a local VM format. | 30/09/2025   | 01/10/2025      | <https://000014.awsstudygroup.com/> |
| 5   | -  Learn about Amazon FSx for Windows File Server. <br> - Understand Multi-AZ deployment. <br> - Distinguish between the two types of file systems: <br>&emsp; + SSD Multi-AZ: High performance, ideal for fast-access workloads. <br>&emsp; + HDD Multi-AZ: Cost-effective, suitable for backups or infrequently accessed data. <br> - Explore advanced FSx features.                  | 01/10/2025   | 02/10/2025      | <https://000025.awsstudygroup.com/> |
| 6   | - Hands-on practice with FSx management: <br>&emsp; + Create and configure File Systems (SSD & HDD). <br>&emsp; + Manage and scale FSx as needed. <br>&emsp; + Monitor performance of the system. năng                                                                                         | 02/10/2025   | 03/10/2025      | <https://000025.awsstudygroup.com/> |


### Week 4 Achievements:

* Clearly understand the VM Import/Export process and how to migrate virtual machines between on-premises and AWS Cloud.
* Have a strong understanding of Amazon FSx for Windows File Server, including its architecture, storage types, and Multi-AZ features.
* Successfully practiced creating and managing SSD Multi-AZ and HDD Multi-AZ File Systems.
* Learned how to create new file shares, enable deduplication and shadow copies, and set up user quotas.
* Monitored and analyzed system performance using CloudWatch metrics and FSx performance reports.
* Efficiently managed user sessions, enabled Continuous Access share, and performed throughput and storage scaling as needed.
