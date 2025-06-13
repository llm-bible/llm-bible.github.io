---
layout: publication
title: 'Efficientllm: Scalable Pruning-aware Pretraining For Architecture-agnostic Edge Language Models'
authors: Xingrun Xing, Zheng Liu, Shitao Xiao, Boyan Gao, Yiming Liang, Wanpeng Zhang, Haokun Lin, Guoqi Li, Jiajun Zhang
conference: "Arxiv"
year: 2025
bibkey: xing2025scalable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.06663'}
  - {name: "Code", url: 'https://github.com/Xingrun-Xing2/EfficientLLM'}
tags: ['Large-Scale Training', 'Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Scaling Laws', 'Pruning', 'Pre-Training', 'Pretraining Methods']
---
Modern large language models (LLMs) driven by scaling laws, achieve
intelligence emergency in large model sizes. Recently, the increasing concerns
about cloud costs, latency, and privacy make it an urgent requirement to
develop compact edge language models. Distinguished from direct pretraining
that bounded by the scaling law, this work proposes the pruning-aware
pretraining, focusing on retaining performance of much larger optimized models.
It features following characteristics: 1) Data-scalable: we introduce minimal
parameter groups in LLM and continuously optimize structural pruning, extending
post-training pruning methods like LLM-Pruner and SparseGPT into the
pretraining phase. 2) Architecture-agnostic: the LLM architecture is
auto-designed using saliency-driven pruning, which is the first time to exceed
SoTA human-designed LLMs in modern pretraining. We reveal that it achieves
top-quality edge language models, termed EfficientLLM, by scaling up LLM
compression and extending its boundary. EfficientLLM significantly outperforms
SoTA baselines with \\(100M \sim 1B\\) parameters, such as MobileLLM, SmolLM,
Qwen2.5-0.5B, OLMo-1B, Llama3.2-1B in common sense benchmarks. As the first
attempt, EfficientLLM bridges the performance gap between traditional LLM
compression and direct pretraining methods, and we will fully open source at
https://github.com/Xingrun-Xing2/EfficientLLM.
