---
title: "Worklog Tuần 11"
.Date: "`r Sys..Date()`"
weight: 2
chapter: false
pre: " <b> 1.11. </b> "
---



### Mục tiêu tuần 11:

* Xây backend chatbot trong Lambda.
* Kết hợp embedding + vector search + Claude Haiku.
* Public API qua API Gateway.
* Test chatbot end-to-end.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Xây logic Lambda: <br>&emsp; + Gọi Cohere để embed query <br>&emsp; + Query PostgreSQL để lấy tài liệu phù hợp                                                                                                  | 16/11/2025 | 17/11/2025      |
| 3   | - Kết hợp Claude Haiku 3: <br>&emsp; + Tạo câu trả lời dựa vào tài liệu tìm được <br>&emsp; + Thêm prompts an toàn + định dạng phản hồi  |17/11/2025 | 18/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Tạo API Gateway: <br>&emsp; + REST API <br>&emsp; + Kết nối Lambda <br>&emsp; + Thêm auth cơ bản | 18/11/2025 | 19/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Test toàn bộ hệ thống: <br>&emsp; + Send user query → Lambda → RDS → Cohere → Claude <br>&emsp; + Ghi log <br>&emsp; + Fix lỗi độ trễ        |19/11/2025 | 20/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Tối ưu hóa: <br>&emsp; + Add caching <br>&emsp; + Cải thiện prompt <br>&emsp; + Tối ưu database                                                                                     | 20/11/2025 | 21/11/2025      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 11:

* Xây hoàn chỉnh backend chatbot bằng Lambda.
* Tích hợp thành công Cohere + PostgreSQL + Claude.
* Triển khai API Gateway hoạt động ổn định.
* Chatbot chạy end-to-end.
* Tối ưu tốc độ và chất lượng phản hồi.
