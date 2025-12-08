---
title: "Event 1"
.Date: "`r Sys..Date()`"
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---



# Bài thu hoạch “AWS Cloud Mastery Series #1”

### Mục Đích Của Sự Kiện

- Chia sẻ kinh nghiệm đi làm ở doanh nghiệp.
- Giới thiệu các mô hình được huấn luyện sẵn của AWS.
- Giới thiệu về bedrock agent core.
- Củng cố kiến thức cho proposal.

### Danh Sách Diễn Giả

- **Dinh Le Hoang Anh** - Cloud Engineer Trainee First Cloud AI Journey
- **Danh Hoang Hieu Nghi** - AI Engineer Renova Cloud
- **Lam Tuan Kiet** - Sr DevOps Engineer FPT Software

### Nội Dung Nổi Bật

#### 1. Tổng quan về AWS AI/ML Services

Phần mở đầu tập trung vào các dịch vụ AI được huấn luyện trước (Pre-trained AI Services) của AWS. Đây là các giải pháp "Ready-to-use", cho phép tích hợp trí tuệ nhân tạo vào ứng dụng mà không cần kiến thức sâu về Data Science hay xây dựng mô hình từ đầu.

#### Các nhóm dịch vụ chính:
* **Computer Vision (Thị giác máy tính):**
    * **Amazon Rekognition:** Phân tích hình ảnh và video (nhận diện khuôn mặt, vật thể, văn bản).
    * **Amazon Lookout (Vision & Equipment):** Các giải pháp cho công nghiệp, giúp phát hiện lỗi sản phẩm và bảo trì dự đoán cho thiết bị.
* **Language & Speech (Ngôn ngữ & Giọng nói):**
    * **Amazon Translate:** Dịch thuật đa ngôn ngữ tự động.
    * **Amazon Textract:** OCR nâng cao, trích xuất văn bản và dữ liệu có cấu trúc từ tài liệu scan.
    * **Amazon Transcribe:** Chuyển đổi giọng nói thành văn bản (Speech-to-Text).
    * **Amazon Polly:** Chuyển đổi văn bản thành giọng nói tự nhiên (Text-to-Speech).
    * **Amazon Comprehend:** NLP service giúp phân tích cảm xúc, từ khóa và ngữ nghĩa văn bản.
* **Search & Personalization:**
    * **Amazon Kendra:** Công cụ tìm kiếm thông minh cho doanh nghiệp.
    * **Amazon Personalize:** Xây dựng hệ thống gợi ý (recommendation) theo thời gian thực.

> **Ghi chú bổ sung:** Giới thiệu về **Pinecone** (trong note là Pinecat) - Đây là một Vector Database quan trọng, thường được sử dụng kết hợp với các dịch vụ AI để lưu trữ embedding.

---

#### 2. Generative AI với Amazon Bedrock

Phần này chuyển trọng tâm từ ML truyền thống sang làn sóng Generative AI (GenAI) và nền tảng Amazon Bedrock.

#### 2.1. Kiến thức nền tảng
* **GenAI là gì?** Phân biệt giữa ML truyền thống (tập trung phân tích/dự đoán) và GenML (tập trung tạo sinh nội dung mới).
* **Foundation Models (FMs):** Bedrock cung cấp quyền truy cập vào các mô hình nền tảng hàng đầu thông qua API.

#### 2.2. Prompt Engineering (Kỹ thuật Prompt)
Các kỹ thuật để tối ưu hóa kết quả đầu ra của mô hình:
* **Zero-Shot Prompting:** Đưa yêu cầu không cần ví dụ mẫu.
* **Few-Shot Prompting:** Cung cấp vài ví dụ (shots) để hướng dẫn mô hình hiểu ngữ cảnh.
* **Chain of Thought (CoT):** Yêu cầu mô hình suy luận từng bước (step-by-step) để giải quyết vấn đề phức tạp.

#### 2.3. Retrieval-Augmented Generation (RAG)
Giải pháp kết hợp LLM với dữ liệu riêng của doanh nghiệp:
* **Embedding:** Sử dụng mô hình **Amazon Titan Embedding** để vector hóa dữ liệu.
* **Knowledge Base:** Quy trình tạo Knowledge Base trên AWS để chatbot có thể tra cứu thông tin chính xác, giảm thiểu ảo giác (hallucination).

---

#### 3. Ứng dụng nâng cao: Bedrock Agents

Mở rộng khả năng của GenAI từ "trả lời" sang "hành động".

* **Bedrock Agent Core:** Cốt lõi của Agent giúp kết nối LLM với các API backend để thực thi tác vụ.
* **Frameworks:** Các công cụ hỗ trợ xây dựng Agent.
* **Tính năng nổi bật:** Khả năng lập kế hoạch (planning), phân rã tác vụ và thực hiện quy trình nghiệp vụ nhiều bước (multi-step workflows).

---

#### 4. Kết luận
Buổi hội thảo cung cấp cái nhìn toàn diện về lộ trình ứng dụng AI trên AWS:
1.  Bắt đầu nhanh với các **Pre-trained Services** (Rekognition, Polly...).
2.  Tận dụng sức mạnh sáng tạo của **GenAI** qua Bedrock.
3.  Tối ưu hóa độ chính xác với **RAG** và **Vector DB** (Pinecone).
4.  Tự động hóa quy trình phức tạp với **Bedrock Agents**.

#### Một số hình ảnh khi tham gia sự kiện
![evt_1](/images/evt_1.jpg)

![evt_2](/images/evt_2.jpg)

![evt_3](/images/evt_3.jpg)
> Tổng thể, sự kiện không chỉ cung cấp kiến thức kỹ thuật mà còn giúp tôi thay đổi cách tư duy về thiết kế ứng dụng, hiện đại hóa hệ thống và phối hợp hiệu quả hơn giữa các team.
