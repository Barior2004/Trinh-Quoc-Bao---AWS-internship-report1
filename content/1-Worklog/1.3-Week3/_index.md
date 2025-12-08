---
title: "Week 3 Worklog"
.Date: "`r Sys..Date()`"
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---

### Week 3 Objectives:

* Gain a deeper understanding of EC2 and S3 services.
* Learn how to create an EC2 instance for configuring Storage Gateway.
* Explore and practice CloudFront for global content delivery.
* Study S3 Cross-Region Replication (CRR) to ensure data availability and redundancy.
* Improve skills in managing AWS resources via both Console and CLI.
* 
### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Improve skills in managing AWS resources via both Console and CLI. <br> - Learn about EBS Volume and Snapshot, including how to create, attach, and detach a volume.                                                                                             | 21/09/2025   | 22/09/2025      |
| 3   | - Learn the fundamentals of Amazon S3 (Simple Storage Service). <br> - Understand key concepts: Bucket, Object, Region, Versioning, Storage Class. <br>- **Practice:** <br>&emsp; + Create an S3 bucket. <br>&emsp; + Upload/download files via AWS Console. <br>&emsp; + Enable Versioning to track data changes.<br>                                            | 22/09/2025   | 23/09/2025      | <https://000057.awsstudygroup.com/vi/> |
| 4   | - Learn about AWS Storage Gateway. <br> - Differentiate between the three types: File Gateway, Volume Gateway, Tape Gateway. Tape. <br> - **Practice:** <br>&emsp; + Launch an EC2 instance to host the Storage Gateway. <br>&emsp; + Configure the Storage Gateway in AWS Console. <br> &emsp; + Connect to S3 for data synchronization. | 23/09/2025   | 24/09/2025      | <https://000024.awsstudygroup.com/vi/> |
| 5   | - Learn about AWS CloudFront. <br> - Understand how Edge Locations and Distributions work.<br> - **Practice**: <br>&emsp; + Create a CloudFront Distribution using data from an S3 bucket.<br>&emsp; + Test access speed from multiple regions.                   | 24/09/2025   | 25/09/2025      | <https://000057.awsstudygroup.com/vi/> |
| 6   | - Learn about S3 Cross-Region Replication (CRR). <br> - **Practice**: <br>&emsp; + Create two buckets in different regions (e.g., Singapore and Tokyo). <br>&emsp; + Enable CRR between the two buckets. <br>&emsp; + Upload a file and verify automatic replication.                                                                                      | 25/09/2025   | 26/09/2025      | <https://000057.awsstudygroup.com/vi/> |


### Week 3 Achievements:

* Clearly understand the relationship between EC2, S3, Storage Gateway, and CloudFront.
* Independently create and manage EC2 instances for various purposes.
* Become proficient in creating, uploading, and managing data within S3.
* Learn how to implement Storage Gateway to synchronize data between on-premises systems and AWS.
* Successfully set up and configure a CloudFront Distribution to optimize content delivery speed.
* Configure S3 Cross-Region Replication (CRR) to ensure high data availability across multiple regions.
* Strengthen AWS resource management skills through both the Console and CLI.

* Amazon S3 Practice
  * Create the first S3 bucket: my-first-s3-demo.
  * Upload files (image, text, CSV) and verify public URLs.
  * Configure Public/Private access, enable Versioning to track file changes.
  * Create a Bucket Policy that allows access only from specific AWS accounts.

* Cross-Region Replication (CRR) Practice
  * Create two buckets:
    * my-bucket-sg (region: Singapore)
    * my-bucket-tokyo (region: Tokyo)
  * Enable Cross-Region Replication between them.
  * Upload a file to my-bucket-sg and confirm it automatically replicates to my-bucket-tokyo.
  * Understand the multi-region replication process, which enhances reliability and data availability.

* EC2 for Storage Gateway Practice
  * Launch an EC2 Instance (Amazon Linux 2 – t2.micro) to install Storage Gateway.
  * Configuration steps:
    * Attach an Elastic IP for stable access.
    * Open required ports: 80, 443, 3260.
    * Install Storage Gateway Appliance on EC2.
  * Connect the EC2 instance to the AWS Storage Gateway Console, select File Gateway type.
  * Create a File Share linked to an existing S3 bucket.
  * Test read/write operations from the Gateway to S3 to verify synchronization.