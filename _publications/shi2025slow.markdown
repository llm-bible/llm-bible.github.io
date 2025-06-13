---
layout: publication
title: 'Slow-fast Architecture For Video Multi-modal Large Language Models'
authors: Min Shi, Shihao Wang, Chieh-yun Chen, Jitesh Jain, Kai Wang, Junjun Xiong, Guilin Liu, Zhiding Yu, Humphrey Shi
conference: "Arxiv"
year: 2025
bibkey: shi2025slow
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01328'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Fine-Tuning']
---
Balancing temporal resolution and spatial detail under limited compute budget
remains a key challenge for video-based multi-modal large language models
(MLLMs). Existing methods typically compress video representations using
predefined rules before feeding them into the LLM, resulting in irreversible
information loss and often ignoring input instructions. To address this, we
propose a novel slow-fast architecture that naturally circumvents this
trade-off, enabling the use of more input frames while preserving spatial
details. Inspired by how humans first skim a video before focusing on relevant
parts, our slow-fast design employs a dual-token strategy: 1) "fast" visual
tokens -- a compact set of compressed video features -- are fed into the LLM
alongside text embeddings to provide a quick overview; 2) "slow" visual tokens
-- uncompressed video features -- are cross-attended by text embeddings through
specially designed hybrid decoder layers, enabling instruction-aware extraction
of relevant visual details with linear complexity. We conduct systematic
exploration to optimize both the overall architecture and key components.
Experiments show that our model significantly outperforms self-attention-only
baselines, extending the input capacity from 16 to 128 frames with just a 3%
increase in computation, and achieving a 16% average performance improvement
across five video understanding benchmarks. Our 7B model achieves
state-of-the-art performance among models of similar size. Furthermore, our
slow-fast architecture is a plug-and-play design that can be integrated into
other video MLLMs to improve efficiency and scalability.
