---
layout: publication
title: 'The Surprising Effectiveness Of Negative Reinforcement In LLM Reasoning'
authors: Xinyu Zhu, Mengzhou Xia, Zhepei Wei, Wei-lin Chen, Danqi Chen, Yu Meng
conference: "Arxiv"
year: 2025
bibkey: zhu2025surprising
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.01347'}
  - {name: "Code", url: 'https://github.com/TianHongZXY/RLVR-Decomposed'}
tags: ['Reinforcement Learning', 'Agentic', 'Has Code', 'Training Techniques']
---
Reinforcement learning with verifiable rewards (RLVR) is a promising approach for training language models (LMs) on reasoning tasks that elicit emergent long chains of thought (CoTs). Unlike supervised learning, it updates the model using both correct and incorrect samples via policy gradients. To better understand its mechanism, we decompose the learning signal into reinforcing correct responses and penalizing incorrect ones, referred to as Positive and Negative Sample Reinforcement (PSR and NSR), respectively. We train Qwen2.5-Math-7B and Qwen3-4B on a mathematical reasoning dataset and uncover a surprising result: training with only negative samples -- without reinforcing correct responses -- can be highly effective: it consistently improves performance over the base model across the entire Pass@\\(k\\) spectrum (\\(k\\) up to \\(256\\)), often matching or surpassing PPO and GRPO. In contrast, reinforcing only correct responses improves Pass@\\(1\\) but degrades performance at higher \\(k\\), due to reduced diversity. These inference-scaling trends highlight that solely penalizing incorrect responses may contribute more to performance than previously recognized. Through gradient analysis, we show that NSR works by suppressing incorrect generations and redistributing probability mass toward other plausible candidates, guided by the model's prior beliefs. It refines the model's existing knowledge rather than introducing entirely new behaviors. Building on this insight, we propose a simple variant of the RL objective that upweights NSR, and show that it consistently improves overall Pass@\\(k\\) performance on MATH, AIME 2025, and AMC23. Our code is available at https://github.com/TianHongZXY/RLVR-Decomposed.
