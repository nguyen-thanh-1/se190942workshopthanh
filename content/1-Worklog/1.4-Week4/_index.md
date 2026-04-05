---
title: "Week 4: Backend & Auth"
date: 2025-01-22
weight: 4
chapter: false
pre: " <b> 1.4. </b> "
---

<!--
{{% notice warning %}}
⚠️ **Note:** The information below is for reference only, please **do not verbatim copy** for your report including this warning.  
{{% /notice %}}
-->

### Goals for week 4: (Practice Phase)
* Focus on Backend development and heavily emphasize improving and refining Prompts for the Pydantic AI agent to optimize the ReAct system, ensuring accurate AI expert responses.
* Build the Backend platform using FastAPI.
   * Lead Backend programming, set up RESTful API Routes and build a centralized Router for exams, connecting AI processing seamlessly and optimizing the fast Streaming logic.
* Implement user authentication system via JWT/Cognito.
* Connect and perform basic CRUD operations on MongoDB Atlas.

### Tasks to be implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | Initialize FastAPI project, config Monorepo structure. <br> + Set up standard directory structure, prepare API Router for the exam workflow. | 26/01 | 26/01 | - |
| Tue | Connect MongoDB Atlas using Motor (async driver) and verify connection. | 27/01 | 27/01 | - |
| Wed | Build Register/Login logic, integrate JWT for RBAC authorization. <br> + Configure JWT middleware to block unauthorized access to Camera/Exam resources. | 28/01 | 28/01 | - |
| Thu | Write CRUD APIs for managing class and exam information. | 29/01 | 29/01 | - |
| Fri | Test API security using Swagger UI and ReDoc. <br> + Optimize error handling (Exception Handlers) in FastAPI. <br> + Summarize the first month and plan AI research. | 30/01 | 30/01 | - |

### Results achieved in week 4:
* Basic Backend system is running stably with FastAPI.
* User authentication and Admin/Teacher/Student authorization are complete. Backend tightly routes APIs to the correct roles.
* Data corresponds and is retrieved successfully from MongoDB Cloud.
