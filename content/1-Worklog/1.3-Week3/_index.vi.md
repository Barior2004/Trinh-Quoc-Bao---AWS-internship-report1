---
title: "Worklog Tuần 3"
.Date: "`r Sys..Date()`"
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---
### Mục tiêu tuần 3:

* Hiểu sâu hơn về dịch vụ EC2 và S3.
* Biết cách tạo EC2 instance phục vụ cho việc cấu hình Storage Gateway.
* Tìm hiểu và thực hành CloudFront để phân phối nội dung toàn cầu.
* Tìm hiểu tính năng Replication Multi-Region trong S3 để đảm bảo tính sẵn sàng và dự phòng dữ liệu.
* Rèn luyện kỹ năng quản lý tài nguyên AWS trên cả Console và CLI.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Ôn lại các khái niệm EC2: Instance type, AMI, Key Pair, Security Group, EBS. <br> - Tìm hiểu EBS Volume và Snapshot, cách tạo, attach và detach volume.                                                                                             | 21/09/2025   | 22/09/2025      |
| 3   | - Tìm hiểu tổng quan về Amazon S3 (Simple Storage Service). <br> - Nắm rõ các khái niệm: Bucket, Object, Region, Versioning, Storage Class. <br>- **Thực hành:** <br>&emsp; + Tạo một S3 Bucket. <br>&emsp; + Upload/Download file qua AWS Console. <br>&emsp; + Bật Versioning để lưu lại lịch sử thay đổi dữ liệu.<br>                                            | 22/09/2025   | 23/09/2025      | <https://000057.awsstudygroup.com/vi/> |
| 4   | - Tìm hiểu AWS Storage Gateway <br> - Phân biệt 3 loại Gateway: File, Volume, Tape. <br> - **Thực hành:** <br>&emsp; + Tạo EC2 instance để chạy Storage Gateway. <br>&emsp; + Cấu hình Storage Gateway trong AWS Console. <br> &emsp; + Kết nối với S3 để đồng bộ dữ liệu. | 23/09/2025   | 24/09/2025      | <https://000024.awsstudygroup.com/vi/> |
| 5   | - Tìm hiểu AWS CloudFront: <br> - Hiểu cơ chế hoạt động của Edge Locations và Distribution.<br> - **Thực hành**: <br>&emsp; + Tạo CloudFront Distribution sử dụng dữ liệu từ S3 Bucket.<br>&emsp; + Kiểm tra tốc độ truy cập từ nhiều khu vực.                   | 24/09/2025   | 25/09/2025      | <https://000057.awsstudygroup.com/vi/> |
| 6   | - Tìm hiểu về Cross-Region Replication (CRR) trong S3. <br> - **Thực hành**: <br>&emsp; + Tạo 2 bucket ở 2 region khác nhau (ví dụ: Singapore và Tokyo). <br>&emsp; + Kích hoạt CRR giữa 2 bucket. <br>&emsp; + Upload file và kiểm tra dữ liệu tự động replicate.                                                                                      | 25/09/2025   | 26/09/2025      | <https://000057.awsstudygroup.com/vi/> |


### Kết quả đạt được tuần 3:

* Hiểu rõ mối liên kết giữa EC2 – S3 – Storage Gateway – CloudFront.
* Tự tạo và quản lý EC2 instance phục vụ các mục đích khác nhau.
* Thành thạo việc tạo, upload, quản lý dữ liệu trong S3.
* Biết cách triển khai Storage Gateway để đồng bộ dữ liệu giữa on-premises và AWS.
* Tạo và cấu hình CloudFront Distribution để tối ưu tốc độ phân phối nội dung.
* Thiết lập thành công Cross-Region Replication trong S3 để đảm bảo tính sẵn sàng dữ liệu trên nhiều vùng.
* Nâng cao kỹ năng thao tác song song trên AWS Console và CLI.

* Thực hành với Amazon S3
  * Tạo bucket đầu tiên: my-first-s3-demo.
  * Upload file (ảnh, text, csv) và kiểm tra đường dẫn công khai.
  * Thiết lập quyền truy cập Public/Private, bật Versioning để quản lý thay đổi của file.
  * Tạo Bucket Policy để chỉ cho phép truy cập từ tài khoản cụ thể.

* Thực hành Cross-Region Replication (CRR)
  * Tạo hai bucket:
    * my-bucket-sg (region: Singapore)
    * my-bucket-tokyo (region: Tokyo)
  * Bật Cross-Region Replication giữa hai bucket.
  * Upload file lên my-bucket-sg, kiểm tra file tự động được replicate sang my-bucket-tokyo.
  * Hiểu rõ quy trình replicate object đa vùng giúp tăng độ tin cậy và sẵn sàng cho dữ liệu.

* Thực hành EC2 cho Storage Gateway
  * Tạo EC2 Instance (Amazon Linux 2 – t2.micro) để cài đặt Storage Gateway.
  * Cấu hình:
    * Gắn Elastic IP để truy cập ổn định.
    * Mở các cổng cần thiết: 80, 443, 3260.
    * Cài đặt Storage Gateway Appliance trên EC2.
  * Kết nối EC2 với AWS Storage Gateway Console, chọn loại File Gateway.
  * Tạo File Share liên kết với S3 bucket đã có.
  * Kiểm tra hoạt động đọc/ghi dữ liệu từ Gateway tới S3.