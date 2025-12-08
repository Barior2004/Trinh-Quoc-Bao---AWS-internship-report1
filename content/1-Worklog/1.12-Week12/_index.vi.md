---
title: "Worklog Tuần 12"
.Date: "`r Sys..Date()`"
weight: 2
chapter: false
pre: " <b> 1.12 </b> "
---


### Mục tiêu tuần 12:

* Chuẩn bị proposal cho dự án chatbot.
* Tổng hợp kiến trúc: Embedding (Cohere) + LLM (Claude Haiku 3) + RDS PostgreSQL + Lambda + API Gateway + NAT Gateway.
* Xác định phạm vi dự án, mục tiêu, milestone.
* Liệt kê các thách thức kỹ thuật và phương án giải quyết.
* Lên kế hoạch bước tiếp theo cho testing và triển khai production.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Review các thành phần đã triển khai: <br>&emsp; + Pipeline embedding Cohere <br>&emsp; + Tích hợp Claude Haiku 3      <br>&emsp; + Lambda functions <br>&emsp; +Lưu trữ vector trong RDS PostgreSQL storage                                                                                             | 23/11/2025 | 24/11/2025      |
| 3   | - Vẽ sơ đồ kiến trúc: <br>&emsp; + API Gateway → Lambda → RDS → Cohere → Claude → Lambda → Response <br>&emsp; + Bao gồm NAT Gateway & thiết kế VPC                                              | 24/11/2025 | 25/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 4   | - Xác định nội dung proposal: <br>&emsp; + Mục tiêu & phạm vi dự án <br>&emsp; + Technology stack <br>&emsp; + Workflow & RAG logic | 25/11/2025 | 26/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 5   | - Liệt kê thách thức tiềm ẩn: <br>&emsp; + Latency <br>&emsp; + Lưu trữ embedding & tối ưu truy vấn <br>&emsp; + LLM prompt design & safety                            | 26/11/2025 | 27/11/2025      | <https://cloudjourney.awsstudygroup.com/> |
| 6   | - Hoàn thiện draft proposal: <br>&emsp; + Bao gồm sơ đồ kiến trúc, mô tả thành phần, milestone, các lưu ý kỹ thuật <br>&emsp; + Chuẩn bị review & feedback                                                                                     | 27/11/2025 | 28/11/2025      | <https://cloudjourney.awsstudygroup.com/> |


### Kết quả đạt được tuần 12:

* Hoàn tất draft proposal dự án chatbot.
* Ghi chép rõ ràng kiến trúc & workflow.
* Nhận diện thách thức kỹ thuật & đề xuất giải pháp.
* Xác định milestone & bước tiếp theo cho triển khai và testing.

