---
layout: publication
title: 'Don''t Do RAG: When Cache-augmented Generation Is All You Need For Knowledge Tasks'
authors: Brian J Chan, Chao-ting Chen, Jui-hung Cheng, Hen-hsen Huang
conference: "Arxiv"
year: 2024
bibkey: chan2024do
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.15605'}
tags: ['Reinforcement Learning', 'RAG', 'Applications']
---
Retrieval-augmented generation (RAG) has gained traction as a powerful
approach for enhancing language models by integrating external knowledge
sources. However, RAG introduces challenges such as retrieval latency,
potential errors in document selection, and increased system complexity. With
the advent of large language models (LLMs) featuring significantly extended
context windows, this paper proposes an alternative paradigm, cache-augmented
generation (CAG) that bypasses real-time retrieval. Our method involves
preloading all relevant resources, especially when the documents or knowledge
for retrieval are of a limited and manageable size, into the LLM's extended
context and caching its runtime parameters. During inference, the model
utilizes these preloaded parameters to answer queries without additional
retrieval steps. Comparative analyses reveal that CAG eliminates retrieval
latency and minimizes retrieval errors while maintaining context relevance.
Performance evaluations across multiple benchmarks highlight scenarios where
long-context LLMs either outperform or complement traditional RAG pipelines.
These findings suggest that, for certain applications, particularly those with
a constrained knowledge base, CAG provide a streamlined and efficient
alternative to RAG, achieving comparable or superior results with reduced
complexity.
