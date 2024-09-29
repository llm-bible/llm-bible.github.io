---
layout: publication
title: The Geometry Of Queries\: Query-based Innovations In Retrieval-augmented Generation
authors: Yang Eric, Amar Jonathan, Lee Jong Ha, Kumar Bhawesh, Jia Yugang
conference: "Arxiv"
year: 2024
bibkey: yang2024geometry
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18044"}
tags: ['Applications', 'RAG']
---
Digital health chatbots powered by Large Language Models (LLMs) have the potential to significantly improve personal health management for chronic conditions by providing accessible and on-demand health coaching and question-answering. However these chatbots risk providing unverified and inaccurate information because LLMs generate responses based on patterns learned from diverse internet data. Retrieval Augmented Generation (RAG) can help mitigate hallucinations and inaccuracies in LLM responses by grounding it on reliable content. However efficiently and accurately retrieving most relevant set of content for real-time user questions remains a challenge. In this work we introduce Query-Based Retrieval Augmented Generation (QB-RAG) a novel approach that pre-computes a database of potential queries from a content base using LLMs. For an incoming patient question QB-RAG efficiently matches it against this pre-generated query database using vector search improving alignment between user questions and the content. We establish a theoretical foundation for QB-RAG and provide a comparative analysis of existing retrieval enhancement techniques for RAG systems. Finally our empirical evaluation demonstrates that QB-RAG significantly improves the accuracy of healthcare question answering paving the way for robust and trustworthy LLM applications in digital health.
