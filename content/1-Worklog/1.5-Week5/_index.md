---
title: "Week 5: AI & Camera Research"
date: 2025-01-29
weight: 5
chapter: false
pre: " <b> 1.5. </b> "
---

<!--
{{% notice warning %}}
⚠️ **Note:** The information below is for reference only, please **do not verbatim copy** for your report including this warning.  
{{% /notice %}}
-->

### Goals for week 5: (Application Phase)
* Integrate the Camera into the web interface. Monitor the workflow running models directly on the user's Client-side resources instead of overloading the server.
* Research integrating YOLO model to monitor the exam room camera.
* Design AI Agentic Workflow architecture for learning support chatbot.
   * Draft the ReAct (Reasoning and Acting) system, allowing the system to automatically route user queries to 1 of 4 specialized Agents (Science, Social, General, Web Search).
* Perform basic object detection tests (phones, faces).

### Tasks to be implemented this week:
| Day | Date | Task |
| --- | --- | --- |
| Mon | 02/02 | Learn about YOLOv8/v10 models for fraud detection problem. |
| Tue | 03/02 | Set up Agentic Workflow for chatbot using Pydantic AI. <br> + Design deep Prompts for each task to ensure Pydantic AI strictly follows rules. |
| Wed | 04/03 | Test detecting multiple faces in a single camera frame. |
| Thu | 05/02 | Design logic flow: Detect violation -> Capture evidence image -> Save to S3. |
| Fri | 06/02 | Research video streaming approaches from Client to Backend. <br> + Optimize prompts for AI Agent to classify student queries. <br> + Evaluate AI latency when processing real-time. |

### Results achieved in week 5:
* Identified a suitable YOLO model for exam monitoring.
* Multi-agent Chatbot architecture is clearly defined. The ReAct model successfully routes specialized queries instead of relying on a single LLM.
* Understood frame capture mechanics and image data transmission from browsers.
