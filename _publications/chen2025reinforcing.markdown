---
layout: publication
title: 'Zipr1: Reinforcing Token Sparsity In Mllms'
authors: Feng Chen, Yefei He, Lequan Lin, Jing Liu, Bohan Zhuang, Qi Wu
conference: "Arxiv"
year: 2025
bibkey: chen2025reinforcing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.18579"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'Transformer', 'Attention Mechanism']
---
Sparse attention mechanisms aim to reduce computational overhead by
selectively processing a subset of salient tokens while preserving model
performance. Despite the effectiveness of such designs, how to actively
encourage token sparsity of well-posed MLLMs remains under-explored, which
fundamentally limits the achievable acceleration effect during inference. In
this paper, we propose a simple RL-based post-training method named
\textbf\{ZipR1\} that treats the token reduction ratio as the efficiency reward
and answer accuracy as the performance reward.
  In this way, our method can jointly alleviate the computation and memory
bottlenecks via directly optimizing the inference-consistent
efficiency-performance tradeoff. Experimental results demonstrate that ZipR1
can reduce the token ratio of Qwen2/2.5-VL from 80% to 25% with a minimal
accuracy reduction on 13 image and video benchmarks.
