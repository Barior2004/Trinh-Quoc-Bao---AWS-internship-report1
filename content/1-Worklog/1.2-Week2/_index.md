---
title: "Week 2 Worklog"
.Date: "`r Sys..Date()`"
weight: 1
chapter: false
pre: " <b> 1.2. </b> "
---
### Week 2 Objectives:

* Understand the concept and role of VPC (Virtual Private Cloud) in AWS infrastructure.
* Learn how to create and configure a VPC (subnet, route table, internet gateway, security group).
* Deploy, connect, and manage EC2 instances within the created VPC.
* Practice managing EC2 instances using both the AWS Management Console and AWS CLI.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start .Date | Completion .Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2   | - Understand what a VPC is and its role in the AWS system. <br> - Learn about the following concepts: <br>&emsp; + VPC, Subnet, Route Table, Internet Gateway, NAT Gateway. <br>&emsp; +  Differentiate between public subnet and private subnet.                                                                                          | 14/09/2025   | 15/09/2025      | <https://www.youtube.com/playlist?list=PLahN4TLWtox2a3vElknwzU_urND8hLn1i/>
| 3   | - Create and configure a VPC. <br> **Practice:** <br>&emsp; + Create a new VPC from scratch. <br>&emsp; + Configure subnet, route table, internet gateway, security group, and NAT gateway.  <br>                                            | 15/09/2025   | 16/09/2025      | <https://000003.awsstudygroup.com/vi/> |
| 4   | -  Learn about EC2.  <br> - Launch and explore different EC2 instance types, AMI, key pair, and security group. <br> - **Practice:** <br>&emsp; 1. Go to EC2 Dashboard → Launch Instance. <br>&emsp; 2. Choose: <br>&emsp;&emsp; - AMI: Amazon Linux 2 <br>&emsp;&emsp; - Instance type: t2.micro (Free Tier)<br>&emsp;&emsp; - Network: select the newly created VPC.<br>&emsp;&emsp; - Subnet: select public subnet.<br>&emsp;&emsp; - Security group: allow SSH (port 22).<br>&emsp; 3.Create or reuse a key pair to SSH into the instance. <br>&emsp; 4. Launch the EC2 instance and verify its status.  | 16/09/2025   | 17/09/2025      | <https://000004.awsstudygroup.com/vi/> |
| 5   | - Connect to the EC2 instance via SSH. <br> Perform some basic EC2 operations using AWS CLI.                   | 17/09/2025   | 18/09/2025      | <https://000004.awsstudygroup.com/vi/> |
| 6   | - Reinforce knowledge and security practices for VPC and EC2. <br> Learn about Security Groups and Network ACLs. <br> + Practice connecting to a private subnet via SSH.                                                                                         | 18/09/2025   | 19/09/2025      | <https://000004.awsstudygroup.com/vi/> |


### Week 2 Achievements:

* Theoretical Understanding

  * Understand the concept of VPC (Virtual Private Cloud) and its role in isolating and controlling networks within AWS.

* Understand the main components of a VPC:

  * Subnet (Public & Private)
  * Route Table
  * Internet Gateway (IGW)
  * NAT Gateway
  * Security Group và Network ACL

* Understand how EC2 (Elastic Compute Cloud) works — a service that provides virtual servers in AWS.

  * Differentiate between the basic concepts:

    * AMI (Amazon Machine Image)
    * Instance type (t2.micro, t3.small, v.v.)
    * Key Pair
    * Elastic IP
    * Security Group

* VPC Hands-on Practice

  * Access the VPC Dashboard to view the default VPC configuration of the AWS account.
  * Create a new custom VPC (CIDR: 10.0.0.0/16).
  * Create two subnets:
    * public-subnet (10.0.1.0/24)
    * private-subnet (10.0.2.0/24)
  * Create an Internet Gateway (IGW) and attach it to the VPC.
  * Create a Route Table and add a route to the IGW for the public subnet.
  * Test network connectivity between subnets and to the Internet.
  
* EC2 Hands-on Practice

  * Select and learn about: Amazon Linux 2, Instance type: t2.micro (Free Tier).
  * Launch an EC2 Instance in the public-subnet of the newly created VPC.
  * Configure:
    * Security Group: allow SSH (port 22) and HTTP (port 80).
    * Key Pair: create a new key file aws-keypair.pem for SSH connection.
    * Successfully connect to the EC2 instance via SSH using the Public IP.