---
layout: publication
title: 'Openrag: Optimizing RAG End-to-end Via In-context Retrieval Learning'
authors: Jiawei Zhou, Lei Chen
conference: "Arxiv"
year: 2025
bibkey: zhou2025optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08398"}
tags: ['RAG', 'Tools', 'Applications']
---
In this paper, we analyze and empirically show that the learned relevance for
conventional information retrieval (IR) scenarios may be inconsistent in
retrieval-augmented generation (RAG) scenarios. To bridge this gap, we
introduce OpenRAG, a RAG framework that is optimized end-to-end by tuning the
retriever to capture in-context relevance, enabling adaptation to the diverse
and evolving needs. Extensive experiments across a wide range of tasks
demonstrate that OpenRAG, by tuning a retriever end-to-end, leads to a
consistent improvement of 4.0% over the original retriever, consistently
outperforming existing state-of-the-art retrievers by 2.1%. Additionally, our
results indicate that for some tasks, an end-to-end tuned 0.2B retriever can
achieve improvements that surpass those of RAG-oriented or instruction-tuned 8B
large language models (LLMs), highlighting the cost-effectiveness of our
approach in enhancing RAG systems.
