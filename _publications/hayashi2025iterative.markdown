---
layout: publication
title: 'Iterkey: Iterative Keyword Generation With Llms For Enhanced Retrieval Augmented Generation'
authors: Kazuki Hayashi, Hidetaka Kamigaito, Shinya Kouda, Taro Watanabe
conference: "Arxiv"
year: 2025
bibkey: hayashi2025iterative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.08450'}
tags: ['Interpretability and Explainability', 'RAG', 'Applications', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability']
---
Retrieval-Augmented Generation (RAG) has emerged as a way to complement the in-context knowledge of Large Language Models (LLMs) by integrating external documents. However, real-world applications demand not only accuracy but also interpretability. While dense retrieval methods provide high accuracy, they lack interpretability; conversely, sparse retrieval methods offer transparency but often fail to capture the full intent of queries due to their reliance on keyword matching. To address these issues, we introduce IterKey, an LLM-driven iterative keyword generation framework that enhances RAG via sparse retrieval. IterKey consists of three LLM-driven stages: generating keywords for retrieval, generating answers based on retrieved documents, and validating the answers. If validation fails, the process iteratively repeats with refined keywords. Across four QA tasks, experimental results show that IterKey achieves 5% to 20% accuracy improvements over BM25-based RAG and simple baselines. Its performance is comparable to dense retrieval-based RAG and prior iterative query refinement methods using dense models. In summary, IterKey is a novel BM25-based approach leveraging LLMs to iteratively refine RAG, effectively balancing accuracy with interpretability.
