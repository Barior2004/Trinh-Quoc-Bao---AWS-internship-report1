---
title: "Week 12 Worklog"
.Date: "`r Sys..Date()`"
weight: 2
chapter: false
pre: " <b> 1.12. </b> "
---


### Week 12 Objectives:

* Prepare project for proposal 
* Summarize architecture: Embedding (Cohere) + LLM (Claude Haiku 3) + RDS PostgreSQL + Lambda + API Gateway + NAT Gateway.
* Define project scope, objectives, and milestones.
* Identify technical challenges and solutions.
* Plan next steps for testing and production deployment.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start .Date | Completion .Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Review all implemented components: <br>&emsp; + Cohere embedding pipeline <br>&emsp; + Claude Haiku 3 integration      <br>&emsp; + Lambda functions <br>&emsp; +RDS PostgreSQL vector storage                                                                                             | 23/11/2025 | 24/11/2025      |
| 3   | - Document architecture diagram: <br>&emsp; + API Gateway → Lambda → RDS → Cohere → Claude → Lambda → Response <br>&emsp; + Include NAT Gateway & VPC design                                              | 24/11/2025 | 25/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Define proposal content: <br>&emsp; + Project objectives & scope <br>&emsp; + Technology stack <br>&emsp; + Workflow & RAG logic | 25/11/2025 | 26/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Identify potential challenges: <br>&emsp; + Latency <br>&emsp; + Embedding storage & query optimization <br>&emsp; + LLM prompt design & safety                            | 26/11/2025 | 27/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Finalize proposal draft: <br>&emsp; + Include architecture diagram, component description, milestones, and technical considerations <br>&emsp; + Prepare for review & feedback                                                                                     | 27/11/2025 | 28/11/2025      | <https://cloudjourney.awsstudygroup.com/> |


### Week 12 Achievements:

* Completed a full proposal draft for chatbot project.
* Documented architecture and workflow clearly.
* Identified technical challenges and proposed solutions.
* Defined milestones and next steps for deployment and testing.
