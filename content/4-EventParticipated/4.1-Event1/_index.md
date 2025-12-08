---
title: "Event 1"
.Date: "`r Sys..Date()`"
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---


# Summary Report: “AWS Cloud Mastery Series #1”

### Event Objectives

- Share experience working in a business.
- Introducing AWS pre-trained models.
- Introducing bedrock agent core.
- Strengthen knowledge for proposal.

### Speakers

- **Dinh Le Hoang Anh** - Cloud Engineer Trainee First Cloud AI Journey
- **Danh Hoang Hieu Nghi** - AI Engineer Renova Cloud
- **Lam Tuan Kiet** - Sr DevOps Engineer FPT Software

### Key Highlights

#### 1. AWS AI/ML Services Overview

The session began with an introduction to AWS Pre-trained AI Services. These are "ready-to-use" solutions that allow developers to add intelligence to applications without needing deep machine learning expertise or building models from scratch.

#### Key Service Categories:
* **Computer Vision:**
    * **Amazon Rekognition:** Image and video analysis (facial recognition, object detection, text detection).
    * **Amazon Lookout (Vision & Equipment):** Industrial solutions for anomaly detection and predictive maintenance.
* **Language & Speech:**
    * **Amazon Translate:** Automated multilingual translation.
    * **Amazon Textract:** Intelligent OCR to extract text and data from scanned documents.
    * **Amazon Transcribe:** Speech-to-Text conversion.
    * **Amazon Polly:** Text-to-Speech conversion with lifelike voices.
    * **Amazon Comprehend:** NLP service for sentiment analysis, keyword extraction, and topic modeling.
* **Search & Personalization:**
    * **Amazon Kendra:** Intelligent enterprise search powered by ML.
    * **Amazon Personalize:** Real-time recommendation system service.

> **Additional Note:** Introduction to **Pinecone** (Vector Database). This is a critical component often used with AI services to store embeddings for semantic search.

---

#### 2. Generative AI with Amazon Bedrock

This section shifted focus from traditional ML to Generative AI (GenAI) and the Amazon Bedrock platform.

#### 2.1. GenAI Fundamentals
* **What is GenAI?** Distinguished between Traditional ML (focused on analysis/prediction) and GenML (focused on generating new content).
* **Foundation Models (FMs):** Bedrock provides API access to leading foundation models.

#### 2.2. Prompt Engineering
Techniques to optimize model outputs:
* **Zero-Shot Prompting:** Making requests without providing examples.
* **Few-Shot Prompting:** Providing a few examples to guide the model's context and format.
* **Chain of Thought (CoT):** Encouraging the model to reason step-by-step to solve complex logic.

#### 2.3. Retrieval-Augmented Generation (RAG)
Combining LLMs with proprietary business data:
* **Embedding:** Using the **Amazon Titan Embedding** model to vectorize text data.
* **Knowledge Base:** The process of creating a Knowledge Base on AWS allows chatbots to retrieve accurate information from internal documents, reducing hallucinations.

---

#### 3. Advanced Workflows: Bedrock Agents

Expanding GenAI capabilities from "answering" to "acting".

* **Bedrock Agent Core:** The core component that connects LLMs to backend APIs to execute tasks.
* **Frameworks:** Tools and frameworks available for building agents.
* **Key Features:** The ability to plan, decompose complex queries, and execute multi-step workflows automatically.

---

#### 4. Conclusion
The workshop provided a comprehensive roadmap for adopting AI on AWS:
1.  Start quickly with **Pre-trained Services** (Rekognition, Polly, etc.).
2.  Leverage the creative power of **GenAI** via Amazon Bedrock.
3.  Enhance accuracy using **RAG** and **Vector DBs** (Pinecone).
4.  Automate complex business processes with **Bedrock Agents**.  

#### Some event photos
![evt_1](/images/evt_1.jpg)

![evt_2](/images/evt_2.jpg)

![evt_3](/images/evt_3.jpg)

> Overall, the event not only provided technical knowledge but also helped me reshape my thinking about application design, system modernization, and cross-team collaboration.
