---
title: "Week 11 Worklog"
.Date: "`r Sys..Date()`"
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---



### Week 11 Objectives:

* Build Chatbot backend logic inside Lambda.
* Integrate embeddings + vector search + LLM response.
* Publish chatbot endpoint using API Gateway.
* Test entire pipeline end-to-end.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start .Date | Completion .Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Build Lambda function: <br>&emsp; + Load embedding from Cohere <br>&emsp; + Query PostgreSQL for top matches                                                                                                  | 16/11/2025 | 17/11/2025      |
| 3   | - Integrate Claude Haiku 3: <br>&emsp; + Use search results to generate final answer <br>&emsp; + Add safety prompts + response formatting  |17/11/2025 | 18/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Build API Gateway endpoint: <br>&emsp; + Create REST API <br>&emsp; + Connect to Lambda <br>&emsp; + Add basic authentication | 18/11/2025 | 19/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - End-to-end testing: <br>&emsp; + Send user query → Lambda → RDS → Cohere → Claude <br>&emsp; + Log responses <br>&emsp; + Fix latency issues        |19/11/2025 | 20/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Optimization: <br>&emsp; + Add caching <br>&emsp; + Improve prompt quality <br>&emsp; + Clean database structure                                                                                     | 20/11/2025 | 21/11/2025      | <https://cloudjourney.awsstudygroup.com/> |


### Week 11 Achievements:

* Built full Lambda backend.
* Completed embedding → retrieval → generation pipeline.
* Successfully deployed API Gateway endpoint.
* Full chatbot running end-to-end with Claude + Cohere + RDS.
* Improved latency & prompt engineering.
