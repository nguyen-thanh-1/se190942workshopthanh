---
title: "Week 9: RAG & AI Chatbot Integration"
date: 2025-02-26
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

<!--
{{% notice warning %}}
⚠️ **Note:** The information below is for reference only, please **do not verbatim copy** for your report including this warning.  
{{% /notice %}}
-->

### Goals for week 9: (Application Phase)
* Finalize the Role authorization entirely. Coordinate attaching completed Backend features to the Frontend and complete the UI for Admin and Students.
* Implement RAG (Retrieval-Augmented Generation) mechanism for the AI system.
   * Gather lecture knowledge into Vectors, ensuring the Bot does not suffer from "hallucination" and strictly follows school materials.
* Build intelligent AI Chatbot interface via Pydantic AI.
* Optimize AI accuracy based on lecture knowledge base.

### Tasks to be implemented this week:
| Day | Task | Start Date | End Date | References |
| --- | --- | --- | --- | --- |
| Mon | Research RAG processes for AI using Pydantic AI. | 02/03 | 02/03 | - |
| Tue | Connect S3 data into Vector Database serving information retrieval. | 03/03 | 03/03 | - |
| Wed | Integrate Multi-agent system to grant Chatbot high expertise. <br> + Channel chat connection API to Next.js via Continuous Streaming for typing effects. | 04/03 | 04/03 | - |
| Thu | Build Chatbot interface with Next.js, supporting Markdown formats. <br> + Coordinate Backend stream responses so the typing flows smoothly without breaking UI. | 05/03 | 05/03 | - |
| Fri | Optimize Prompt Engineering to enhance response quality. <br> + Test Chatbot features on both Web and Mobile interfaces. <br> + Evaluate Chatbot efficiency with the AI development team. | 06/03 | 06/03 | - |

### Results achieved in week 9:
* Chatbot is capable of answering questions based on lecture content.
* Friendly Chatbot interface, fast response speeds thanks to asynchronous processing.
* RAG process operates stably, guaranteeing accurate information for AI.
