---
layout: publication
title: 'Dynamicrag: Leveraging Outputs Of Large Language Model As Feedback For Dynamic Reranking In Retrieval-augmented Generation'
authors: Jiashuo Sun, Xianrui Zhong, Sizhe Zhou, Jiawei Han
conference: "Arxiv"
year: 2025
bibkey: sun2025leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.07233"}
  - {name: "Code", url: "https://github.com/GasolSun36/DynamicRAG"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'RAG', 'Interpretability', 'Has Code', 'Interpretability and Explainability']
---
Retrieval-augmented generation (RAG) systems combine large language models (LLMs) with external knowledge retrieval, making them highly effective for knowledge-intensive tasks. A crucial but often under-explored component of these systems is the reranker. Since irrelevant documents in RAG systems can mislead the generator, the reranker plays a vital role in refining retrieved documents to enhance generation quality and explainability. However, it is challenging to determine the appropriate number of documents (\\(k\\)) that the reranker should select: too few may result in missing critical information, while too many introduce noise and inefficiencies. Although recent studies have explored LLM-based rerankers, they primarily leverage internal model knowledge and overlook the rich supervisory signals that LLMs can provide, such as using response quality as feedback for optimizing reranking decisions. In this paper, we propose DynamicRAG, a novel RAG framework where the reranker dynamically adjusts both the order and number of retrieved documents based on the query. We model the reranker as an agent optimized through reinforcement learning (RL), using rewards derived from LLM output quality. Across seven knowledge-intensive datasets, DynamicRAG demonstrates superior performance, achieving state-of-the-art results among models of same parameter sizes. The model, data and code are available at https://github.com/GasolSun36/DynamicRAG.
