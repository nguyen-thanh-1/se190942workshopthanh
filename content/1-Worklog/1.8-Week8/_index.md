---
title: "Week 8: Data & Reporting"
date: 2025-02-19
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

<!--
{{% notice warning %}}
⚠️ **Note:** The information below is for reference only, please **do not verbatim copy** for your report including this warning.  
{{% /notice %}}
-->

### Goals for week 8: (Application Phase)
* Implement flow logic closely following the UI role division (Admin, Teacher, Student) with appropriate functional groups and strict security.
* Build module for managing and reporting student exam results.
   * Focus on extracting exam data (Excel/CSV) linked with fraud history for precise reporting.
* Integrate automated notification service (Amazon SES).
* Optimize data retrieval performance from MongoDB.

### Tasks to be implemented this week:
| Day | Date | Task |
| --- | --- | --- |
| Mon | 23/02 | Develop the feature for teachers to view the list of participating students. <br> + Connect S3 fraud report data directly to the visual dashboard. |
| Tue | 24/02 | Program logic for exporting exam results to Excel/CSV format. |
| Wed | 25/02 | Integrate Amazon SES to automatically email results to students. |
| Thu | 26/02 | Setup Redis to cache search results and class lists. |
| Fri | 27/02 | Fix Vietnamese formatting bugs when exporting reports from MongoDB. <br> + Test real email flow with Amazon SES account. <br> + Review reporting module source code with Backend team. |

### Results achieved in week 8:
* System can manage and export professional report data. Completed full export flows with FrontEnd visualizing fraud evidence.
* Automated the exam result notification process via Email.
* Data retrieval speed increased significantly thanks to Redis Caching.
