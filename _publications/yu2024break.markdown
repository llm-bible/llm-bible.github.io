---
layout: publication
title: 'Break The Id-language Barrier: An Adaption Framework For Sequential Recommendation'
authors: Xiaohan Yu, Li Zhang, Xin Zhao, Yue Wang
conference: "Arxiv"
year: 2024
bibkey: yu2024break
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.18262"}
tags: ['Model Architecture', 'Fine-Tuning', 'Tools']
---
The recent breakthrough of large language models (LLMs) in natural language
processing has sparked exploration in recommendation systems, however, their
limited domain-specific knowledge remains a critical bottleneck. Specifically,
LLMs lack key pieces of information crucial for sequential recommendations,
such as user behavior patterns. To address this critical gap, we propose
IDLE-Adapter, a novel framework that integrates pre-trained ID embeddings, rich
in domain-specific knowledge, into LLMs to improve recommendation accuracy.
IDLE-Adapter acts as a bridge, transforming sparse user-item interaction data
into dense, LLM-compatible representations through a Pre-trained ID Sequential
Model, Dimensionality Alignment, Layer-wise Embedding Refinement, and
Layer-wise Distribution Alignment. Furthermore, IDLE-Adapter demonstrates
remarkable flexibility by seamlessly integrating ID embeddings from diverse
ID-based sequential models and LLM architectures. Extensive experiments across
various datasets demonstrate the superiority of IDLE-Adapter, achieving over
10% and 20% improvements in HitRate@5 and NDCG@5 metrics, respectively,
compared to state-of-the-art methods.
