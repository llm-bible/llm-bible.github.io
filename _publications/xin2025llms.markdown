---
layout: publication
title: 'Llms As Better Recommenders With Natural Language Collaborative Signals: A Self-assessing Retrieval Approach'
authors: Haoran Xin, Ying Sun, Chao Wang, Weijia Zhang, Hui Xiong
conference: "Arxiv"
year: 2025
bibkey: xin2025llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.19464"}
tags: ['Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Prompting']
---
Incorporating collaborative information (CI) effectively is crucial for leveraging LLMs in recommendation tasks. Existing approaches often encode CI using soft tokens or abstract identifiers, which introduces a semantic misalignment with the LLM's natural language pretraining and hampers knowledge integration. To address this, we propose expressing CI directly in natural language to better align with LLMs' semantic space. We achieve this by retrieving a curated set of the most relevant user behaviors in natural language form. However, identifying informative CI is challenging due to the complexity of similarity and utility assessment. To tackle this, we introduce a Self-assessing COllaborative REtrieval framework (SCORE) following the retrieve-rerank paradigm. First, a Collaborative Retriever (CAR) is developed to consider both collaborative patterns and semantic similarity. Then, a Self-assessing Reranker (SARE) leverages LLMs' own reasoning to assess and prioritize retrieved behaviors. Finally, the selected behaviors are prepended to the LLM prompt as natural-language CI to guide recommendation. Extensive experiments on two public datasets validate the effectiveness of SCORE in improving LLM-based recommendation.
