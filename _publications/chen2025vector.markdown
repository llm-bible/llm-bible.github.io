---
layout: publication
title: 'Retroinfer: A Vector-storage Approach For Scalable Long-context LLM Inference'
authors: Yaoqi Chen, Jinkai Zhang, Baotong Lu, Qianxi Zhang, Chengruidong Zhang, Jingjia Luo, Di Liu, Huiqiang Jiang, Qi Chen, Jing Liu, Bailu Ding, Xiao Yan, Jiawei Jiang, Chen Chen, Mingxing Zhang, Yuqing Yang, Fan Yang, Mao Yang
conference: "Arxiv"
year: 2025
bibkey: chen2025vector
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.02922"}
tags: ['Model Architecture', 'Reinforcement Learning', 'RAG', 'Vector Indexing', 'Attention Mechanism']
---
The growing context lengths of large language models (LLMs) pose significant
challenges for efficient inference, primarily due to GPU memory and bandwidth
constraints. We present RetroInfer, a novel system that reconceptualizes the
key-value (KV) cache as a vector storage system which exploits the inherent
attention sparsity to accelerate long-context LLM inference. At its core is the
wave index, an Attention-aWare VEctor index that enables efficient and accurate
retrieval of critical tokens through techniques such as tripartite attention
approximation, accuracy-bounded attention estimation, and segmented clustering.
Complementing this is the wave buffer, which coordinates KV cache placement and
overlaps computation and data transfer across GPU and CPU to sustain high
throughput. Unlike prior sparsity-based methods that struggle with token
selection and hardware coordination, RetroInfer delivers robust performance
without compromising model accuracy. Experiments on long-context benchmarks
show up to 4.5X speedup over full attention within GPU memory limits and up to
10.5X over sparse attention baselines when KV cache is extended to CPU memory,
all while preserving full-attention-level accuracy.
