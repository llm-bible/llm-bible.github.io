---
layout: publication
title: 'Empowering Graphrag With Knowledge Filtering And Integration'
authors: Kai Guo, Harry Shomer, Shenglai Zeng, Haoyu Han, Yu Wang, Jiliang Tang
conference: "Arxiv"
year: 2025
bibkey: guo2025empowering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13804'}
tags: ['RAG', 'Applications', 'Tools']
---
In recent years, large language models (LLMs) have revolutionized the field
of natural language processing. However, they often suffer from knowledge gaps
and hallucinations. Graph retrieval-augmented generation (GraphRAG) enhances
LLM reasoning by integrating structured knowledge from external graphs.
However, we identify two key challenges that plague GraphRAG:(1) Retrieving
noisy and irrelevant information can degrade performance and (2)Excessive
reliance on external knowledge suppresses the model's intrinsic reasoning. To
address these issues, we propose GraphRAG-FI (Filtering and Integration),
consisting of GraphRAG-Filtering and GraphRAG-Integration. GraphRAG-Filtering
employs a two-stage filtering mechanism to refine retrieved information.
GraphRAG-Integration employs a logits-based selection strategy to balance
external knowledge from GraphRAG with the LLM's intrinsic reasoning,reducing
over-reliance on retrievals. Experiments on knowledge graph QA tasks
demonstrate that GraphRAG-FI significantly improves reasoning performance
across multiple backbone models, establishing a more reliable and effective
GraphRAG framework.
