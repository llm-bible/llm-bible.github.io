---
layout: publication
title: 'Inverse Reinforcement Learning With Dynamic Reward Scaling For LLM Alignment'
authors: Ruoxi Cheng, Haoxuan Ma, Weixin Wang, Zhiqiang Wang, Xiaoshuang Jia, Simeng Qin, Xiaochun Cao, Yang Liu, Xiaojun Jia
conference: "Arxiv"
year: 2025
bibkey: cheng2025inverse
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.18991'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Responsible AI', 'Pretraining Methods']
---
Robust alignment is vital for safely deploying large language models (LLMs). Existing techniques are either reward-based -- training a reward model on preference pairs and optimizing with reinforcement learning (RL) -- or reward-free -- directly fine-tuning on ranked outputs. Recent research shows that well-tuned reward-based pipelines remain the most robust, and single-response demonstrations can outperform pairwise preference data. However, two key challenges remain: (i) imbalanced safety datasets that over-represent common hazards while neglecting long-tail threats; and (ii) static reward models that ignore task difficulty, limiting optimization efficiency and attainable gains. To address these limitations, we propose \textbf\{DR-IRL\}, which dynamically adjusts rewards through inverse reinforcement learning. We first construct a balanced safety dataset of seven harmful categories using Chain-of-Draft (CoD) template prompts, which reduce token usage and generation time compared to Chain-of-Thought (CoT). We then train category-specific reward models on this dataset via IRL. Finally, to align the LLM, we introduce \textbf\{GRPO-S\} (Group Relative Policy Optimization--Scaling), a variant of GRPO that scales the reward during optimization to task difficulty -- data-level hardness measured by CLIP similarity and model-level responsiveness measured by reward gaps. Extensive experiments on multiple benchmarks and LLMs demonstrate that DR-IRL outperforms all baselines in safety alignment while maintaining usefulness.
