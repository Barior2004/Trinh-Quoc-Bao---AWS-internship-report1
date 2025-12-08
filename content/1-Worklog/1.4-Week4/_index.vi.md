---
title: "Worklog Tuần 4"
.Date: "`r Sys..Date()`"
weight: 1
chapter: false
pre: " <b> 1.4. </b> "
---
### Mục tiêu tuần 4:

* Hiểu rõ khái niệm VM Import/Export và lý do tại sao doanh nghiệp cần tính năng này.
* Biết cách import máy ảo (VM) từ môi trường on-premises lên AWS và export ngược lại khi cần.
* Làm quen với dịch vụ Amazon FSx for Windows File Server, hiểu cơ chế hoạt động, ưu điểm, và các tình huống sử dụng thực tế.
* Thực hành tạo, cấu hình và quản lý FSx File System.
* Nâng cao khả năng thao tác CLI và Console để xử lý các dịch vụ lưu trữ

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu khái niệm VM Import/Export trong AWS. <br> - Tìm hiểu vai trò của S3 và IAM Role trong quá trình import/export. <br> - Hiểu được mục đích: <br>&emsp; + Di chuyển máy ảo từ on-premises lên EC2. <br>&emsp; +  Dự phòng hoặc backup VM giữa môi trường local và cloud.                                                                                           | 28/09/2025   | 29/09/2025      | <https://000014.awsstudygroup.com/>
| 3   | - Chuẩn bị môi trường cho VM Import/Export <br> - **Thực hành:** <br>&emsp; + Tạo S3 bucket để lưu trữ file máy ảo. <br>&emsp; + Cấu hình IAM Role (vmimport) với các quyền cần thiết. <br>&emsp; + Cài đặt AWS CLI và kiểm tra thông tin tài khoản.                                           | 29/09/2025   | 30/09/2025      | <https://000014.awsstudygroup.com/> |
| 4   | - Thực hành import máy ảo vào EC2 <br> - Sau khi hoàn tất, khởi tạo instance từ AMI được tạo ra. <br> - Thực hành export EC2 instance về dạng máy ảo local | 30/09/2025   | 01/10/2025      | <https://000014.awsstudygroup.com/> |
| 5   | -  Tìm hiểu dịch vụ Amazon FSx for Windows File Server <br> - Hiểu về Multi-AZ deployment <br> - Phân biệt hai loại file system: <br>&emsp; + SSD Multi-AZ: Hiệu năng cao, thích hợp cho workload truy cập nhanh <br>&emsp; + HDD Multi-AZ: Chi phí thấp, phù hợp cho lưu trữ bản ghi, sao lưu hoặc dữ liệu ít truy cập. <br> - Tìm hiểu về các tính năng nâng cao của FSx                  | 01/10/2025   | 02/10/2025      | <https://000025.awsstudygroup.com/> |
| 6   | - Thực hành triển khai và quản trị FSx <br>&emsp; + Tạo và cấu hình File System <br>&emsp; + Quản lý và mở rộng FSx <br>&emsp; + Theo dõi hiệu năng                                                                                         | 02/10/2025   | 03/10/2025      | <https://000025.awsstudygroup.com/> |


### Kết quả đạt được tuần 4:

* Hiểu rõ quy trình VM Import/Export, có thể di chuyển máy ảo giữa môi trường on-premises và AWS Cloud.
* Nắm vững kiến thức về Amazon FSx for Windows File Server, bao gồm kiến trúc, loại lưu trữ, và tính năng Multi-AZ.
* Thực hành tạo và quản lý thành công SSD Multi-AZ và HDD Multi-AZ File Systems.
* Biết cách tạo file share mới, bật deduplication, shadow copies, và thiết lập user quotas.
* Theo dõi và đánh giá hiệu năng hệ thống bằng CloudWatch metrics và FSx performance reports.
* Quản lý hiệu quả các phiên làm việc của người dùng, bật Continuous Access share, và thực hiện scaling throughput & storage khi cần thiết.

