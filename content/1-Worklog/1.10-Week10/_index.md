---
title: "Week 10 Worklog"
.Date: "`r Sys..Date()`"
weight: 2
chapter: false
pre: " <b> 1.10. </b> "
---


### Week 10 Objectives:

* Understand the architecture of a serverless chatbot.
* Learn how embedding models (Cohere Embed v3) work.
* Understand vector search logic and how RDS PostgreSQL stores embeddings.
* Learn Claude Haiku 3 for LLM generation.
* Prepare AWS infrastructure: Lambda, VPC, NAT Gateway.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start .Date | Completion .Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Learn chatbot architecture <br> - Understand the RAG workflow                                                                                                   | 09/11/2025 | 10/11/2025      |
| 3   | - Study Cohere Embedding Model (Embed v3): <br>&emsp; + How embedding vectors work <br>&emsp; + Chunking content <br>&emsp; + Cosine similarity overview   | 10/11/2025 | 11/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Hands-on with embeddings: <br>&emsp; + Generate embeddings from sample text <br>&emsp; + Store vectors inside RDS PostgreSQL table <br>&emsp; + Test vector similarity query | 11/11/2025 | 12/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Learn Claude 3 Haiku basics: <br>&emsp; + Prompting <br>&emsp; + System message <br>&emsp; + Temperature & max tokens                            | 12/11/2025 | 13/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Set up AWS environment: <br>&emsp; + Create Lambda inside VPC <br>&emsp; + NAT Gateway for outbound internet <br>&emsp; + Connect Lambda to RDS PostgreSQL                                                                                     | 13/11/2025 | 14/11/2025      | <https://cloudjourney.awsstudygroup.com/> |


### Week 10 Achievements:

* Understood chatbot and RAG architecture.
* Learned Cohere embeddings and vector similarity.
* Successfully stored and queried embeddings in PostgreSQL.
* Learned how Claude Haiku 3 handles generation.
* Deployed Lambda + NAT Gateway + VPC environment.
