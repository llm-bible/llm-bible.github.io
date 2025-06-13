---
layout: publication
title: 'Subgcache: Accelerating Graph-based RAG With Subgraph-level KV Cache'
authors: Qiuyu Zhu, Liang Zhang, Qianxiong Xu, Cheng Long, Jie Zhang
conference: "Arxiv"
year: 2025
bibkey: zhu2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.10951"}
tags: ['RAG', 'Tools', 'Prompting']
---
Graph-based retrieval-augmented generation (RAG) enables large language models (LLMs) to incorporate structured knowledge via graph retrieval as contextual input, enhancing more accurate and context-aware reasoning. We observe that for different queries, it could retrieve similar subgraphs as prompts, and thus we propose SubGCache, which aims to reduce inference latency by reusing computation across queries with similar structural prompts (i.e., subgraphs). Specifically, SubGCache clusters queries based on subgraph embeddings, constructs a representative subgraph for each cluster, and pre-computes the key-value (KV) cache of the representative subgraph. For each query with its retrieved subgraph within a cluster, it reuses the pre-computed KV cache of the representative subgraph of the cluster without computing the KV tensors again for saving computation. Experiments on two new datasets across multiple LLM backbones and graph-based RAG frameworks demonstrate that SubGCache consistently reduces inference latency with comparable and even improved generation quality, achieving up to 6.68\\(\times\\) reduction in time-to-first-token (TTFT).
