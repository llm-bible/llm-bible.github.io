---
layout: publication
title: 'Demystifying Domain-adaptive Post-training For Financial Llms'
authors: Zixuan Ke, Yifei Ming, Xuan-phi Nguyen, Caiming Xiong, Shafiq Joty
conference: "Arxiv"
year: 2025
bibkey: ke2025demystifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.04961"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Distillation']
---
Domain-adaptive post-training of large language models (LLMs) has emerged as
a promising approach for specialized domains such as medicine and finance.
However, significant challenges remain in identifying optimal adaptation
criteria and training strategies across varying data and model configurations.
To address these challenges, we introduce FINDAP, a systematic and fine-grained
investigation into domain adaptive post-training of LLMs for the finance
domain. Our approach consists of four key components: FinCap, which defines the
core capabilities required for the target domain; FinRec, an effective training
recipe that jointly optimizes continual pre-training and instruction-following,
along with a novel preference data distillation method leveraging process
signals from a generative reward model; FinTrain, a curated set of training
datasets supporting FinRec; and FinEval, a comprehensive evaluation suite
aligned with FinCap. The resulting model, Llama-Fin, achieves state-of-the-art
performance across a wide range of financial tasks. Our analysis also
highlights how each post-training stage contributes to distinct capabilities,
uncovering specific challenges and effective solutions, providing valuable
insights for domain adaptation of LLMs.
