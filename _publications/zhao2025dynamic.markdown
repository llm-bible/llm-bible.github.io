---
layout: publication
title: 'Skipgpt: Dynamic Layer Pruning Reinvented With Token Awareness And Module Decoupling'
authors: Anhao Zhao, Fanghua Ye, Yingqi Fan, Junlong Tong, Zhiwei Fei, Hui Su, Xiaoyu Shen
conference: "Arxiv"
year: 2025
bibkey: zhao2025dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04179"}
  - {name: "Code", url: "https://github.com/EIT-NLP/SkipGPT"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Pruning', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Has Code', 'Attention Mechanism']
---
Large language models (LLMs) achieve remarkable performance across tasks but incur substantial computational costs due to their deep, multi-layered architectures. Layer pruning has emerged as a strategy to alleviate these inefficiencies, but conventional static pruning methods overlook two critical dynamics inherent to LLM inference: (1) horizontal dynamics, where token-level heterogeneity demands context-aware pruning decisions, and (2) vertical dynamics, where the distinct functional roles of MLP and self-attention layers necessitate component-specific pruning policies. We introduce SkipGPT, a dynamic layer pruning framework designed to optimize computational resource allocation through two core innovations: (1) global token-aware routing to prioritize critical tokens, and (2) decoupled pruning policies for MLP and self-attention components. To mitigate training instability, we propose a two-stage optimization paradigm: first, a disentangled training phase that learns routing strategies via soft parameterization to avoid premature pruning decisions, followed by parameter-efficient LoRA fine-tuning to restore performance impacted by layer removal. Extensive experiments demonstrate that SkipGPT reduces over 40% of model parameters while matching or exceeding the performance of the original dense model across benchmarks. By harmonizing dynamic efficiency with preserved expressivity, SkipGPT advances the practical deployment of scalable, resource-aware LLMs. Our code is publicly available at: https://github.com/EIT-NLP/SkipGPT.
