---
layout: publication
title: 'Insight-rag: Enhancing Llms With Insight-driven Augmentation'
authors: Pouya Pezeshkpour, Estevam Hruschka
conference: "Arxiv"
year: 2025
bibkey: pezeshkpour2025insight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.00187"}
tags: ['RAG', 'Tools', 'Applications', 'Reinforcement Learning']
---
Retrieval Augmented Generation (RAG) frameworks have shown significant
promise in leveraging external knowledge to enhance the performance of large
language models (LLMs). However, conventional RAG methods often retrieve
documents based solely on surface-level relevance, leading to many issues: they
may overlook deeply buried information within individual documents, miss
relevant insights spanning multiple sources, and are not well-suited for tasks
beyond traditional question answering. In this paper, we propose Insight-RAG, a
novel framework designed to address these issues. In the initial stage of
Insight-RAG, instead of using traditional retrieval methods, we employ an LLM
to analyze the input query and task, extracting the underlying informational
requirements. In the subsequent stage, a specialized LLM -- trained on the
document database -- is queried to mine content that directly addresses these
identified insights. Finally, by integrating the original query with the
retrieved insights, similar to conventional RAG approaches, we employ a final
LLM to generate a contextually enriched and accurate response. Using two
scientific paper datasets, we created evaluation benchmarks targeting each of
the mentioned issues and assessed Insight-RAG against traditional RAG pipeline.
Our results demonstrate that the Insight-RAG pipeline successfully addresses
these challenges, outperforming existing methods by a significant margin in
most cases. These findings suggest that integrating insight-driven retrieval
within the RAG framework not only enhances performance but also broadens the
applicability of RAG to tasks beyond conventional question answering.
