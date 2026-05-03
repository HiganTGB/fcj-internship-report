---
title: "Worklog Tuần 5"
date: 2026-04-06
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---



### Mục tiêu tuần 5:
* Thống nhất đề tài
* Tìm hiểu về Amazon Simple Storage Service(AWS S3),Amazon CloudFront
* Tìm hiểu về Amazon Simple Notification Service (SNS), Amazon Simple Queue Service (SQS), AWS Lambda.
* Thiết lập các mô hình bằng Terraform

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc                                                                                                                                                                                   | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu                            |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ | --------------- | ----------------------------------------- |
| 2   | - Thống nhất đề tài <br> - Tìm hiểu về AWS S3    <br> **Thực hành:** <br>&emsp; + Thiết lập website tĩnh cho AWS S3 và áp dụng Amazon CloudFront cho S3                                                                                  | 06/04/2026   | 06/04/2026      |https://000057.awsstudygroup.com/
| 4   | - Tìm hiểu về SNS <br> **Thực hành:** <br>&emsp; + Thiết lập SNS bằng giao diện, terraform                                           | 08/04/2026   | 08/04/2026      | https://000077.awsstudygroup.com/ |
| 6   | - Tìm hiểu về SQS, AWS Lambda <br>  **Thực hành:** <br>&emsp; + Thiết lập SQS bằng giao diện, terraform , kết nối SQS với  SNS thông qua AWS Lambda                                        | 10/04/2026   | 10/04/2026      | https://000077.awsstudygroup.com/ |

### Kết quả đạt được tuần 5:

* Hiểu được các thành phần của SNS:
  * Topic
  * Publisher
  * Subscriber
* Hiểu được các hoạt động của SQS:
  * Mô hình hoạt động : Pull (kéo)
  * Producer,Queue,Consumer
* Hiểu được Lambda và mô hình hoạt động:
  * Event-driven
  * Scaling
  * Các ngôn ngữ và thư viện hỗ trợ
* Đã tạo và cấu hình theo mô hình bằng giao diện và terraform:
  * SNS Topic -> SQS Queue -> Consumer (Lambda)
  * SQS Queue -> Consumer(Lambda) -> SNS Topic


