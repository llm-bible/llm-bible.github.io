---
layout: publication
title: 'Agent-unirag: A Trainable Open-source LLM Agent Framework For Unified Retrieval-augmented Generation Systems'
authors: Hoang Pham, Thuy-duong Nguyen, Khac-hoai Nam Bui
conference: "Arxiv"
year: 2025
bibkey: pham2025agent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22571"}
tags: ['Agentic', 'Tools', 'Applications', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Merging']
---
This paper presents a novel approach for unified retrieval-augmented generation (RAG) systems using the recent emerging large language model (LLM) agent concept. Specifically, Agent LLM, which utilizes LLM as fundamental controllers, has become a promising approach to enable the interpretability of RAG tasks, especially for complex reasoning question-answering systems (e.g., multi-hop queries). Nonetheless, previous works mainly focus on solving RAG systems with either single-hop or multi-hop approaches separately, which limits the application of those approaches to real-world applications. In this study, we propose a trainable agent framework called Agent-UniRAG for unified retrieval-augmented LLM systems, which enhances the effectiveness and interpretability of RAG systems. The main idea is to design an LLM agent framework to solve RAG tasks step-by-step based on the complexity of the inputs, simultaneously including single-hop and multi-hop queries in an end-to-end manner. Furthermore, we introduce SynAgent-RAG, a synthetic dataset to enable the proposed agent framework for small open-source LLMs (e.g., Llama-3-8B). The results show comparable performances with closed-source and larger open-source LLMs across various RAG benchmarks. Our source code and dataset are publicly available for further exploitation.
