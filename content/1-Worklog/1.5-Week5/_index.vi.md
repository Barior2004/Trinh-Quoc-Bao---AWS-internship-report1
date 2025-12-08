---
title: "Worklog Tuần 5"
.Date: "`r Sys..Date()`"
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---

### Mục tiêu tuần 5:

* Hiểu rõ dịch vụ AWS Security Hub và cách nó tổng hợp các phát hiện bảo mật từ nhiều nguồn.
* Biết cách kích hoạt, cấu hình và phân tích các tiêu chuẩn bảo mật (CIS, PCI-DSS, AWS Foundational Best Practices).
* Hiểu AWS Key Management Service (KMS), các cơ chế mã hóa, key policy, CMK và các tình huống sử dụng thực tế.
* Thực hành tạo, quản lý và xoay vòng (rotation) khóa KMS.
* Tìm hiểu AWS Identity Center, bao gồm Permission Sets, nguồn danh tính (Identity Sources) và cách quản lý người dùng/nhóm.
* Nâng cao kỹ năng triển khai các dịch vụ bảo mật thông qua cả AWS Console và AWS CLI.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Tìm hiểu AWS Security Hub: <br>&emsp; + Security Hub dùng để làm gì, tổng hợp phát hiện ra sao.. <br>&emsp; +Khái niệm Insights, Findings và các tích hợp                                                                                                    | 05/10/2025 | 06/10/2025      | <https://000018.awsstudygroup.com/2-enable-sec-hub/>
| 3   | - Thực hành với Security Hub: <br>&emsp; + Bật CIS standard và phân tích những control failed phổ biến. <br>&emsp; + Xem và phân tích Findings chi tiết. <br>&emsp; + Phân biệt Security Hub – GuardDuty – Inspector <br>                                              | 06/10/2025 | 07/10/2025      | <https://000018.awsstudygroup.com/2-enable-sec-hub/> |
| 4   | - Tìm hiểu AWS Key Management Service (KMS): <br>&emsp; + Khái niệm CMK, khóa đối xứng / bất đối xứng. <br>&emsp; + Cách hoạt động của Key Policy và quyền IAM. <br>&emsp; + Envelope Encryption & cách các dịch vụ AWS dùng KMS.  | 07/10/2025 | 08/10/2025      | <https://000033.awsstudygroup.com/> |
| 5   | - Thực hành với KMS: <br>&emsp; + Mã hóa / giải mã dữ liệu bằng AWS CLI. <br>&emsp; + Tích hợp KMS với S3, EBS, RDS, Lambda environment variables. <br>&emsp; + Bật Key Rotation. <br>&emsp; + Kiểm thử disable key & schedule key deletion.
 deletion.                            | 08/10/2025 | 09/10/2025      | <https://000033.awsstudygroup.com/> |
| 6   | - Tìm hiểu & thực hành AWS Identity Center: <br>&emsp; + Hiểu về identity sources <br>&emsp; + Learn Permission Sets <br>&emsp; + Gán người dùng/nhóm vào các tài khoản AWS. <br>&emsp; +Kiểm thử quy trình đăng nhập và chuyển đổi role.                                                                               | 09/10/2025 | 10/10/2025      | <https://000012.awsstudygroup.com/vi/> |


### Kết quả đạt được tuần 5:

* Hiểu rõ cách hoạt động của AWS Security Hub và các tiêu chuẩn bảo mật trong AWS.
* Đã bật và cấu hình thành công Security Hub
* Hiểu được vai trò của KMS trong việc mã hóa dữ liệu trên các dịch vụ AWS
* Rèn luyện kỹ năng trong AWS Identity Center: quản lý người dùng, nhóm, bộ quyền và quyền truy cập liên tài khoản.
* Cải thiện kiến ​​thức tổng thể về các biện pháp bảo mật tốt nhất của AWS.


