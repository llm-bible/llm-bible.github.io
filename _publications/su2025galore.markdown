---
layout: publication
title: 'Galore 2: Large-scale LLM Pre-training By Gradient Low-rank Projection'
authors: Dijia Su, Andrew Gu, Jane Xu, Yuandong Tian, Jiawei Zhao
conference: "Arxiv"
year: 2025
bibkey: su2025galore
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.20437'}
tags: ['Large-Scale Training', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Quantization', 'Pre-Training']
---
Large language models (LLMs) have revolutionized natural language
understanding and generation but face significant memory bottlenecks during
training. GaLore, Gradient Low-Rank Projection, addresses this issue by
leveraging the inherent low-rank structure of weight gradients, enabling
substantial memory savings without sacrificing performance. Recent works
further extend GaLore from various aspects, including low-bit quantization and
higher-order tensor structures. However, there are several remaining challenges
for GaLore, such as the computational overhead of SVD for subspace updates and
the integration with state-of-the-art training parallelization strategies
(e.g., FSDP). In this paper, we present GaLore 2, an efficient and scalable
GaLore framework that addresses these challenges and incorporates recent
advancements. In addition, we demonstrate the scalability of GaLore 2 by
pre-training Llama 7B from scratch using up to 500 billion training tokens,
highlighting its potential impact on real LLM pre-training scenarios.
