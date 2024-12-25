---
layout: page
title: AI Tutor
description: LLM-based educational platform for course help.
img: assets/img/terrier.png
importance: 2
category: work
giscus_comments: false
---

Earlier this year, we launched Edubotics.ai, an open-source platform for deploying LLM-powered academic assistants. These assistants are designed to provide 24/7 support to students by answering common questions and offering guidance. Its primary use is to supplement instructor and teaching assistant advisement, making help readily available even outside of regular office hours. They benefit students by offering instant assistance, thereby enhancing their learning experience and allowing them to resolve queries quickly. We intend to use Edubotics.ai to develop a suite of AI-based tools for academic settings.

Over the past few months I worked on improving the data processing and retrieval mechanisms. I built a pipeline powered by GPT4o to turn visually complex PDF content into Markdown for the language model's easy understanding. It handled mathematical notations, charts and even complex graphs and images, turning them into detailed descriptions. This ensured that responses are grounded and consistent with course material like lecture PDFs. I also implemented an agentic approach to RAG, where the assistant chooses from a number of vectorstores to retrieve them given a query. A question on assignments get routed to the vectorstore that stores assignments, and a question on lectures gets routed to the lecture vectorstore. This narrows the search, enhancing precision. This approach saw the retrival success rate on assignment-based queries go up by 70%. Right now I'm working on more sophisticated agentic orchestration, to enable features like multi-step planning for Socratic-style assistance and intervention mechanisms.

An experimental AI tutor built with Edubotics was piloted this fall (2024) in DS701: Master's Tools for Data Science class to gather feedback and monitor performance. It's available on [HuggingFace space](https://huggingface.co/spaces/dl4ds/dl4ds_tutor).
