---
title: "Week 5 Worklog"
date: 2026-04-06
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---
### Week 5 Objectives:

* Finalize the project topic.
* Learn about Amazon Simple Storage Service (AWS S3) and Amazon CloudFront.
* Learn about Amazon Simple Notification Service (SNS), Amazon Simple Queue Service (SQS), and AWS Lambda.
* Set up architectural models using Terraform.

### Tasks to be carried out this week:

| Days | Tasks | Start Date | Completion Date | Reference Material |
| :--- | :--- | :--- | :--- | :--- |
| Mon | - Research AWS S3 <br> **Practice:** <br>&emsp; + Set up a static website on AWS S3 and apply Amazon CloudFront | 06/04/2026 | 06/04/2026 | [https://000057.awsstudygroup.com/](https://000057.awsstudygroup.com/) |
| Wed | - Research SNS <br> **Practice:** <br>&emsp; + Set up SNS via Management Console and Terraform | 08/04/2026 | 08/04/2026 | [https://000077.awsstudygroup.com/](https://000077.awsstudygroup.com/) |
| Fri | - Research SQS and AWS Lambda <br> **Practice:** <br>&emsp; + Set up SQS via Management Console and Terraform; connect SQS with SNS through AWS Lambda | 10/04/2026 | 10/04/2026 | [https://000077.awsstudygroup.com/](https://000077.awsstudygroup.com/) |

### Week 5 Achievements:

* Understood the core components of **SNS**:
  * Topic
  * Publisher
  * Subscriber
* Understood **SQS** operations:
  * Communication model: Pull (polling)
  * Producer, Queue, and Consumer
* Understood **Lambda** and its operational model:
  * Event-driven architecture
  * Automatic scaling
  * Supported languages and libraries
* Successfully created and configured architectures using both the Console and Terraform:
  * SNS Topic -> SQS Queue -> Consumer (Lambda)
  * SQS Queue -> Consumer (Lambda) -> SNS Topic