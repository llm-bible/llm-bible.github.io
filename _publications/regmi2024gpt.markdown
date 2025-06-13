---
layout: publication
title: 'GPT Semantic Cache: Reducing LLM Costs And Latency Via Semantic Embedding Caching'
authors: Sajal Regmi, Chetan Phakami Pun
conference: "Arxiv"
year: 2024
bibkey: regmi2024gpt
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.05276'}
tags: ['RAG', 'Efficiency and Optimization', 'Model Architecture', 'Applications', 'Tools', 'GPT']
---
Large Language Models (LLMs), such as GPT, have revolutionized artificial
intelligence by enabling nuanced understanding and generation of human-like
text across a wide range of applications. However, the high computational and
financial costs associated with frequent API calls to these models present a
substantial bottleneck, especially for applications like customer service
chatbots that handle repetitive queries. In this paper, we introduce GPT
Semantic Cache, a method that leverages semantic caching of query embeddings in
in-memory storage (Redis). By storing embeddings of user queries, our approach
efficiently identifies semantically similar questions, allowing for the
retrieval of pre-generated responses without redundant API calls to the LLM.
This technique achieves a notable reduction in operational costs while
significantly enhancing response times, making it a robust solution for
optimizing LLM-powered applications. Our experiments demonstrate that GPT
Semantic Cache reduces API calls by up to 68.8% across various query
categories, with cache hit rates ranging from 61.6% to 68.8%. Additionally, the
system achieves high accuracy, with positive hit rates exceeding 97%,
confirming the reliability of cached responses. This technique not only reduces
operational costs, but also improves response times, enhancing the efficiency
of LLM-powered applications.
