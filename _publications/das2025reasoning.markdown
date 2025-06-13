---
layout: publication
title: 'Rader: Reasoning-aware Dense Retrieval Models'
authors: Debrup Das, Sam O' Nuallain, Razieh Rahimi
conference: "Arxiv"
year: 2025
bibkey: das2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18405"}
tags: ['RAG', 'Training Techniques']
---
We propose RaDeR, a set of reasoning-based dense retrieval models trained with data derived from mathematical problem solving using large language models (LLMs). Our method leverages retrieval-augmented reasoning trajectories of an LLM and self-reflective relevance evaluation, enabling the creation of both diverse and hard-negative samples for reasoning-intensive relevance. RaDeR retrievers, trained for mathematical reasoning, effectively generalize to diverse reasoning tasks in the BRIGHT and RAR-b benchmarks, consistently outperforming strong baselines in overall performance. Notably, RaDeR achieves significantly higher performance than baselines on the Math and Coding splits. In addition, RaDeR presents the first dense retriever that outperforms BM25 when queries are Chain-of-Thought reasoning steps, underscoring the critical role of reasoning-based retrieval to augment reasoning language models. Furthermore, RaDeR achieves comparable or superior performance while using only 2.5% of the training data used by the concurrent work REASONIR, highlighting the quality of our synthesized training data.
