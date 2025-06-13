---
layout: publication
title: 'Hypercube-rag: Hypercube-based Retrieval-augmented Generation For In-domain Scientific Question-answering'
authors: Jimeng Shi, Sizhe Zhou, Bowen Jin, Wei Hu, Shaowen Wang, Giri Narasimhan, Jiawei Han
conference: "Arxiv"
year: 2025
bibkey: shi2025hypercube
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19288"}
  - {name: "Code", url: "https://github.com/JimengShi/Hypercube-RAG"}
tags: ['Tools', 'Efficiency and Optimization', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Interpretability', 'Has Code']
---
Large language models (LLMs) often need to incorporate external knowledge to solve theme-specific problems. Retrieval-augmented generation (RAG), which empowers LLMs to generate more qualified responses with retrieved external data and knowledge, has shown its high promise. However, traditional semantic similarity-based RAGs struggle to return concise yet highly relevant information for domain knowledge-intensive tasks, such as scientific question-answering (QA). Built on a multi-dimensional (cube) structure called Hypercube, which can index documents in an application-driven, human-defined, multi-dimensional space, we introduce the Hypercube-RAG, a novel RAG framework for precise and efficient retrieval. Given a query, Hypercube-RAG first decomposes it based on its entities and topics and then retrieves relevant documents from cubes by aligning these decomposed components with hypercube dimensions. Experiments on three in-domain scientific QA datasets demonstrate that our method improves accuracy by 3.7% and boosts retrieval efficiency by 81.2%, measured as relative gains over the strongest RAG baseline. More importantly, our Hypercube-RAG inherently offers explainability by revealing the underlying predefined hypercube dimensions used for retrieval. The code and data sets are available at https://github.com/JimengShi/Hypercube-RAG.
