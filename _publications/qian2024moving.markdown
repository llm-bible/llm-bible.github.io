---
layout: publication
title: Memorag\: Moving Towards Next-gen RAG Via Memory-inspired Knowledge Discovery
authors: Qian Hongjin, Zhang Peitian, Liu Zheng, Mao Kelong, Dou Zhicheng
conference: "Arxiv"
year: 2024
bibkey: qian2024moving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.05591"}
tags: ['Model Architecture', 'RAG', 'Tools']
---
Retrieval-Augmented Generation (RAG) leverages retrieval tools to access external databases thereby enhancing the generation quality of large language models (LLMs) through optimized context. However the existing retrieval methods are constrained inherently as they can only perform relevance matching between explicitly stated queries and well-formed knowledge but unable to handle tasks involving ambiguous information needs or unstructured knowledge. Consequently existing RAG systems are primarily effective for straightforward question-answering tasks. In this work we propose MemoRAG a novel retrieval-augmented generation paradigm empowered by long-term memory. MemoRAG adopts a dual-system architecture. On the one hand it employs a light but long-range LLM to form the global memory of database. Once a task is presented it generates draft answers cluing the retrieval tools to locate useful information within the database. On the other hand it leverages an expensive but expressive LLM which generates the ultimate answer based on the retrieved information. Building on this general framework we further optimize MemoRAGs performance by enhancing its cluing mechanism and memorization capacity. In our experiment MemoRAG achieves superior performance across a variety of evaluation tasks including both complex ones where conventional RAG fails and straightforward ones where RAG is commonly applied.
