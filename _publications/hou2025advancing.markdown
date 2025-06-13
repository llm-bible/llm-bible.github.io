---
layout: publication
title: 'Advancing Language Model Reasoning Through Reinforcement Learning And Inference Scaling'
authors: Zhenyu Hou, Xin Lv, Rui Lu, Jiajie Zhang, Yujiang Li, Zijun Yao, Juanzi Li, Jie Tang, Yuxiao Dong
conference: "Arxiv"
year: 2025
bibkey: hou2025advancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.11651"}
  - {name: "Code", url: "https://github.com/THUDM/T1"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Large language models (LLMs) have demonstrated remarkable capabilities in
complex reasoning tasks. However, existing approaches mainly rely on imitation
learning and struggle to achieve effective test-time scaling. While
reinforcement learning (RL) holds promise for enabling self-exploration and
learning from feedback, recent attempts yield only modest improvements in
complex reasoning. In this paper, we present T1 to scale RL by encouraging
exploration and understand inference scaling. We first initialize the LLM using
synthesized chain-of-thought data that integrates trial-and-error and
self-verification. To scale RL training, we promote increased sampling
diversity through oversampling. We further employ an entropy bonus as an
auxiliary loss, alongside a dynamic anchor for regularization to facilitate
reward optimization. We demonstrate that T1 with open LLMs as its base exhibits
inference scaling behavior and achieves superior performance on challenging
math reasoning benchmarks. For example, T1 with Qwen2.5-32B as the base model
outperforms the recent Qwen QwQ-32B-Preview model on MATH500, AIME2024, and
Omni-math-500. More importantly, we present a simple strategy to examine
inference scaling, where increased inference budgets directly lead to T1's
better performance without any additional verification. We will open-source the
T1 models and the data used to train them at \url\{https://github.com/THUDM/T1\}.
