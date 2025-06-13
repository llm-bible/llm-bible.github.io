---
layout: publication
title: 'Skewroute: Training-free LLM Routing For Knowledge Graph Retrieval-augmented Generation Via Score Skewness Of Retrieved Context'
authors: Hairu Wang, Yuan Feng, Yukun Cao, Xike Xie, S Kevin Zhou
conference: "Arxiv"
year: 2025
bibkey: wang2025training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23841'}
tags: ['Training Techniques', 'RAG', 'Applications', 'Tools']
---
Large language models excel at many tasks but often incur high inference costs during deployment. To mitigate hallucination, many systems use a knowledge graph to enhance retrieval-augmented generation (KG-RAG). However, the large amount of retrieved knowledge contexts increase these inference costs further. A promising solution to balance performance and cost is LLM routing, which directs simple queries to smaller LLMs and complex ones to larger LLMs. However, no dedicated routing methods currently exist for RAG, and existing training-based routers face challenges scaling to this domain due to the need for extensive training data. We observe that the score distributions produced by the retrieval scorer strongly correlate with query difficulty. Based on this, we propose a novel, training-free routing framework, the first tailored to KG-RAG that effectively balances performance and cost in a plug-and-play manner. Experiments show our method reduces calls to larger LLMs by up to 50% without sacrificing response quality, demonstrating its potential for efficient and scalable LLM deployment.
