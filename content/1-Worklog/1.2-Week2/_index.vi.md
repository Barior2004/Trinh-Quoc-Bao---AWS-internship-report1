---
title: "Worklog Tuần 2"
.Date: "`r Sys..Date()`"
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---
### Mục tiêu tuần 2:

* Hiểu khái niệm và vai trò của VPC trong hạ tầng AWS.
* Biết cách tạo và cấu hình VPC (subnet, route table, internet gateway, security group).
* Triển khai, kết nối và quản lý EC2 instance trong VPC vừa tạo.
* Thực hành quản lý EC2 qua AWS Console và AWS CLI.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Hiểu rõ VPC là gì, vai trò của nó trong hệ thống AWS <br> - Tìm hiểu về khái niệm: <br>&emsp; + VPC, Subnet, Route Table, Internet Gateway, NAT Gateway. <br>&emsp; +  Phân biệt giữa public subnet và private subnet.                                                                                          | 14/09/2025   | 15/09/2025      | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i/>
| 3   | - Tạo và cấu hình VPC <br> **Thực hành:** <br>&emsp; + Tạo một VPC mới từ đầu. <br>&emsp; + Cấu hình subnet, route table, internet gateway, sercurity group, NAT gateway.  <br>                                            | 15/09/2025   | 16/09/2025      | <https://000003.awsstudygroup.com/vi/> |
| 4   | -  Tìm hiểu về EC2  <br> - Launch và tìm hiểu các loại EC2 instance, AMI, key pair, security group <br> - **Thực hành:** <br>&emsp; 1. Vào EC2 Dashboard → Launch Instance. <br>&emsp; 2. Chọn: <br>&emsp;&emsp; - AMI: Amazon Linux 2 <br>&emsp;&emsp; - Instance type: t2.micro (Free Tier)<br>&emsp;&emsp; - Network: chọn VPC vừa tạo.<br>&emsp;&emsp; - Subnet: chọn public-subnet.<br>&emsp;&emsp; - Security group: cho phép SSH (port 22).<br>&emsp; 3.Tạo hoặc sử dụng lại key pair để SSH vào máy. <br>&emsp; 4. Khởi tạo EC2 và kiểm tra trạng thái.  | 16/09/2025   | 17/09/2025      | <https://000004.awsstudygroup.com/vi/> |
| 5   | - Kết nối EC2 instance qua SSH. <br> Thực hiện một số thao tác cơ bản với EC2 qua AWS CLI.                   | 17/09/2025   | 18/09/2025      | <https://000004.awsstudygroup.com/vi/> |
| 6   | - Củng cố kiến thức và bảo mật VPC + EC2. <br> Tìm hiểu Security Group và Network ACL. <br> + Kết nối SSH private subnet                                                                                         | 18/09/2025   | 19/09/2025      | <https://000004.awsstudygroup.com/vi/> |


### Kết quả đạt được tuần 2:

* Hiểu biết lý thuyết

  * Nắm được khái niệm VPC (Virtual Private Cloud) và vai trò trong việc cô lập, kiểm soát mạng trong AWS.

* Hiểu được các thành phần chính của một VPC:

  * Subnet (Public & Private)
  * Route Table
  * Internet Gateway (IGW)
  * NAT Gateway
  * Security Group và Network ACL

* Nắm được cơ chế hoạt động của EC2 (Elastic Compute Cloud) — dịch vụ cung cấp máy chủ ảo trong AWS.

  * Phân biệt các khái niệm cơ bản:

    * AMI (Amazon Machine Image)
    * Instance type (t2.micro, t3.small, v.v.)
    * Key Pair
    * Elastic IP
    * Security Group

* Thực hành với VPC

  * Truy cập VPC Dashboard để xem cấu hình VPC mặc định của tài khoản AWS.
  * Tạo mới một VPC riêng (CIDR: 10.0.0.0/16).
  * Tạo 2 subnet:
    * public-subnet (10.0.1.0/24)
    * private-subnet (10.0.2.0/24)
  * Tạo Internet Gateway và gắn vào VPC.
  * Tạo Route Table, gán route tới IGW cho subnet public.
  * Kiểm tra khả năng kết nối mạng giữa các subnet và ra Internet.
  
* Thực hành với EC2

  * Tìm hiểu và chọn AMI: Amazon Linux 2, Instance type: t2.micro (Free Tier).
  * Tạo EC2 Instance nằm trong public-subnet thuộc VPC mới.
  * Cấu hình:
    * Security Group: cho phép SSH (port 22) và HTTP (port 80).
    * Key Pair: tạo mới aws-keypair.pem để kết nối SSH.
    * Kết nối SSH thành công tới EC2 qua Public IP