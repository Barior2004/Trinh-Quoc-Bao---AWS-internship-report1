---
title: "Event 2"
.Date: "`r Sys..Date()`"
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---



# Bài thu hoạch “BUILDING AGENTIC AI Context Optimization with Amazon Bedrock”

### Mục Đích Của Sự Kiện

- Phân tích chuyên sâu về khả năng của tác nhân Amazon Bedrock, bao gồm các khái niệm cốt lõi, kiến ​​trúc và các tính năng chính để xây dựng tác nhân AI trên AWS.
- Bài thuyết trình về trường hợp sử dụng thực tế của CEO Diaflow, giới thiệu cách triển khai thực tế quy trình làm việc của agentic bằng cách sử dụng dịch vụ AWS.
- Tổng quan ngắn gọn về công ty và giới thiệu sản phẩm của người đồng sáng lập CloudThinker, nêu bật nền tảng điều phối AI của họ.
- Phiên họp kỹ thuật nâng cao (L300) khám phá khuôn khổ phối hợp của CloudThinker và các kỹ thuật tối ưu hóa ngữ cảnh trên Amazon Bedrock.
- Workshop lập trình tương tác với các kỹ sư CloudThinker, tập trung vào việc triển khai thực tế.

### Danh Sách Diễn Giả

- **Kien Nguyen** - Solutions Architect Amazon Web Services
- **Viet Pham** -Founder cum CEO Diaflow
- **Thang Ton** - Co-founder & COO CloudThinker
- **Henry Bui** - Head of Engineering CloudThinker
- **Kha Van** - Community Leader Amazon Web Services

### Nội Dung Nổi Bật

#### 1. Phân tích chuyên sâu: Amazon Bedrock Agents
Phần đầu tiên tập trung vào việc mổ xẻ khả năng của **Amazon Bedrock Agents**, chuyển dịch từ việc sử dụng LLM thụ động sang các tác nhân AI chủ động.

* **Khái niệm cốt lõi (Core Concepts):** Agent không chỉ trả lời câu hỏi mà còn có khả năng lập kế hoạch (planning) và sử dụng công cụ (tools) để hoàn thành mục tiêu.
* **Kiến trúc (Architecture):**
    * Kết nối Foundation Models (FMs) với các nguồn dữ liệu doanh nghiệp và API.
    * Cơ chế "Chain-of-Thought" giúp Agent tự động phân rã yêu cầu phức tạp thành các bước nhỏ để thực thi.
* **Tính năng chính:**
    * Quản lý bộ nhớ (Memory management) để duy trì ngữ cảnh hội thoại.
    * Khả năng truy xuất kiến thức (RAG) tích hợp sẵn.
    * Tracing: Theo dõi quá trình suy luận của Agent để debug và tối ưu hóa.

---

#### 2. Case Study thực tế: Diaflow

Bài tham luận chia sẻ về cách **Diaflow** đã hiện thực hóa khái niệm "Agentic Workflow" vào sản phẩm thực tế:
* **Triển khai:** Sử dụng các dịch vụ AWS để xây dựng luồng công việc tự động hóa, nơi các Agent đóng vai trò như những nhân viên ảo xử lý tác vụ cụ thể.
* **Bài học kinh nghiệm:** Cách xử lý các thách thức khi đưa Agent vào môi trường production, đảm bảo độ tin cậy và phản hồi chính xác trong các tình huống thực tế.

---

#### 3. Giải pháp Điều phối AI: CloudThinker Overview

Giới thiệu về **CloudThinker** và vai trò của nền tảng điều phối (Orchestration Platform) trong hệ sinh thái AI:
* **Vấn đề:** Khi hệ thống AI phức tạp lên, việc quản lý nhiều model và nhiều agent trở nên khó khăn.
* **Giải pháp:** CloudThinker cung cấp lớp điều phối giúp quản lý, giám sát và tối ưu hóa sự tương tác giữa các thành phần AI, giúp doanh nghiệp tập trung vào logic nghiệp vụ thay vì hạ tầng.

---

#### 4. Phiên kỹ thuật nâng cao (L300): Orchestration & Context Optimization

* **Khuôn khổ phối hợp (Orchestration Framework):**
    * Cách thiết kế hệ thống để nhiều Agent có thể cộng tác (Multi-agent collaboration).
    * Điều hướng luồng xử lý (Routing) thông minh đến đúng Agent chuyên trách.
* **Tối ưu hóa ngữ cảnh (Context Optimization):**
    * Kỹ thuật quản lý cửa sổ ngữ cảnh (Context Window) của LLM trên Bedrock.
    * Cách chọn lọc thông tin quan trọng để đưa vào prompt, giúp giảm chi phí token và tăng độ chính xác cho câu trả lời.

---

#### 5. Workshop: Lập trình tương tác (Interactive Coding)

Phần thực hành tập trung vào việc triển khai thực tế ("Hands-on"):
* **Nội dung:** Viết code để tích hợp framework của CloudThinker với Amazon Bedrock.
* **Kết quả:** Xây dựng thành công một quy trình Agent cơ bản, từ việc nhận yêu cầu, xử lý ngữ cảnh đến việc gọi API thực thi tác vụ.

---

#### 6. Tổng kết
Sự kiện đã mở ra hướng đi mới trong việc phát triển ứng dụng AI:
1.  **Agentic AI là tương lai:** Chuyển từ Chatbot hỏi-đáp sang Agent thực thi hành động.
2.  **Tầm quan trọng của Orchestration:** Cần một lớp điều phối mạnh mẽ (như CloudThinker) để quản lý các hệ thống AI phức tạp.
3.  **Tối ưu hóa là chìa khóa:** Việc quản lý ngữ cảnh hiệu quả trên Bedrock quyết định trực tiếp đến hiệu năng và chi phí của dự án.

#### Một số hình ảnh khi tham gia sự kiện
![evt_4](/images/evt_4.jpg)

![evt_5](/images/evt_5.jpg)

![evt_6](/images/evt_6.jpg)
> Tổng thể, sự kiện không chỉ cung cấp kiến thức kỹ thuật mà còn giúp tôi thay đổi cách tư duy về thiết kế ứng dụng, hiện đại hóa hệ thống và phối hợp hiệu quả hơn giữa các team.
