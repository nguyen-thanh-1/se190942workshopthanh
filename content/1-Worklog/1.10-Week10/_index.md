---
title: "Week 10: Monitoring & Optimization"
date: 2025-03-05
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

<!--
{{% notice warning %}}
⚠️ **Note:** The information below is for reference only, please **do not verbatim copy** for your report including this warning.  
{{% /notice %}}
-->

### Goals for week 10: (Completion Phase)
* Begin testing the entire system via AWS Amplify, reviewing late Frontend features and final APIs.
* Set up performance monitoring system and real-time logs via CloudWatch.
   * Add monitoring for Backend logs (FastAPI), making it easier to Debug and see how long AI Agents take to respond.
* Optimize structural security and automatic data backups.
* Test EduTrust system load bearing capacity (Stress Test).
   * Simulate a large number of students taking exams and pushing snapshots continuously to S3 to discover real-world bandwidth limits.

### Tasks to be implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | Configure AWS CloudWatch to monitor logs from FastAPI and Next.js. | 09/03 | 09/03 | - |
| Tue | Debug and optimize response times of AI Agents. | 10/03 | 10/03 | - |
| Wed | Setup auto Backup processes for MongoDB Atlas. | 11/03 | 11/03 | - |
| Thu | Check S3 Bucket security, ensuring access strictly via Presigned URLs. | 12/03 | 12/03 | - |
| Fri | Perform Stress Test simulating many students testing simultaneously. <br> + Gauge the AWS EC2 Load Balancer limit under heavy simultaneous API calls. <br> + Refine system operation and administration guides. <br> + Verify Docker containers stability on AWS environment. | 13/03 | 13/03 | - |

### Results achieved in week 10:
* System is closely monitored, ready to respond to technical incidents. Continuous Logfire logs from Pydantic AI push smoothly to Cloudwatch.
* Automated data backup guarantees student exam safety.
* Understand system load limits to prepare Scaling plans.
