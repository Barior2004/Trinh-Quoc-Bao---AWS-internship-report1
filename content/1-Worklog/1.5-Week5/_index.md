---
title: "Week 5 Worklog"
.Date: "`r Sys..Date()`"
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---



### Week 5 Objectives:

* Understand AWS Security Hub and how it centralizes security findings.
* Learn how to enable, configure, and interpret Security Hub security standards (CIS, PCI-DSS, Foundational Best Practices).
* Understand AWS Key Management Service (KMS), its encryption mechanisms, key policies, CMKs, and use cases.
* Practice creating, managing, and rotating encryption keys.
* Learn AWS Identity Center (Successor to AWS SSO), including permission sets, identity sources, and user/group access management.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start .Date | Completion .Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Learn about AWS Security Hub: <br>&emsp; + Understand what Security Hub does and how it aggregates security findings. <br>&emsp; +Understand the concept of Insights, Findings, and Integrations                                                                                                    | 05/10/2025 | 06/10/2025      | <https://000018.awsstudygroup.com/2-enable-sec-hub/>
| 3   | - Practice hands-on with Security Hub: <br>&emsp; + Enable CIS standard & interpret common failed controls. <br>&emsp; + View and analyze Findings. <br>&emsp; + Compare Security Hub vs GuardDuty vs Inspector <br>                                              | 06/10/2025 | 07/10/2025      | <https://000018.awsstudygroup.com/2-enable-sec-hub/> |
| 4   | - Learn about AWS Key Management Service (KMS): <br>&emsp; + Understand CMK, symmetric vs asymmetric keys. <br>&emsp; + Grant, Key Policy, IAM Permission interaction. <br>&emsp; + Envelope Encryption & how AWS Services integrate with KMS.  | 07/10/2025 | 08/10/2025      | <https://000033.awsstudygroup.com/> |
| 5   | - Hands-on with KMS operations: <br>&emsp; + Encrypt/Decrypt data locally using AWS CLI. <br>&emsp; + Use KMS with S3, EBS, RDS, Lambda environment variables. <br>&emsp; + Enable Key Rotation. <br>&emsp; + Test disabling & scheduling key deletion.                            | 08/10/2025 | 09/10/2025      | <https://000033.awsstudygroup.com/> |
| 6   | - Learn & practice AWS Identity Center (AWS SSO): <br>&emsp; + Understand identity sources <br>&emsp; + Learn Permission Sets <br>&emsp; + Assign users/groups to AWS accounts with Permission Sets. <br>&emsp; +Test login flow and switching roles.                                                                               | 09/10/2025 | 10/10/2025      | <https://000012.awsstudygroup.com/vi/> |


### Week 5 Achievements:

* Gained a solid understanding of AWS Security Hub’s architecture, security standards, and how to interpret aggregated findings.
* Successfully enabled and configured Security Hub
* Understood the roles of KMS in encrypting data across AWS services
* Gained skills in AWS Identity Center: managing users, groups, permission sets, and cross-account access.
* Improved overall knowledge about AWS security best practices.