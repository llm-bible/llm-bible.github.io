---
layout: publication
title: 'Beyond RAG: Task-aware KV Cache Compression For Comprehensive Knowledge Reasoning'
authors: Giulio Corallo, Orion Weller, Fabio Petroni, Paolo Papotti
conference: "Arxiv"
year: 2025
bibkey: corallo2025beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04973'}
tags: ['Few-Shot', 'RAG', 'Applications']
---
Incorporating external knowledge in large language models (LLMs) enhances
their utility across diverse applications, but existing methods have
trade-offs. Retrieval-Augmented Generation (RAG) fetches evidence via
similarity search, but key information may fall outside top ranked results.
Long-context models can process multiple documents but are computationally
expensive and limited by context window size. Inspired by students condensing
study material for open-book exams, we propose task-aware key-value (KV) cache
compression, which compresses external knowledge in a zero- or few-shot setup.
This enables LLMs to reason efficiently over a compacted representation of all
relevant information. Experiments show our approach outperforms both RAG and
task-agnostic compression methods. On LongBench v2, it improves accuracy by up
to 7 absolute points over RAG with a 30x compression rate, while reducing
inference latency from 0.43s to 0.16s. A synthetic dataset highlights that RAG
performs well when sparse evidence suffices, whereas task-aware compression is
superior for broad knowledge tasks.
