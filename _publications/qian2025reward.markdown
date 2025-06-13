---
layout: publication
title: 'Toolrl: Reward Is All Tool Learning Needs'
authors: Cheng Qian, Emre Can Acikgoz, Qi He, Hongru Wang, Xiusi Chen, Dilek Hakkani-tür, Gokhan Tur, Heng Ji
conference: "Arxiv"
year: 2025
bibkey: qian2025reward
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.13958"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Survey Paper', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Current Large Language Models (LLMs) often undergo supervised fine-tuning
(SFT) to acquire tool use capabilities. However, SFT struggles to generalize to
unfamiliar or complex tool use scenarios. Recent advancements in reinforcement
learning (RL), particularly with R1-like models, have demonstrated promising
reasoning and generalization abilities. Yet, reward design for tool use
presents unique challenges: multiple tools may be invoked with diverse
parameters, and coarse-grained reward signals, such as answer matching, fail to
offer the finegrained feedback required for effective learning. In this work,
we present the first comprehensive study on reward design for tool selection
and application tasks within the RL paradigm. We systematically explore a wide
range of reward strategies, analyzing their types, scales, granularity, and
temporal dynamics. Building on these insights, we propose a principled reward
design tailored for tool use tasks and apply it to train LLMs using Group
Relative Policy Optimization (GRPO). Empirical evaluations across diverse
benchmarks demonstrate that our approach yields robust, scalable, and stable
training, achieving a 17% improvement over base models and a 15% gain over SFT
models. These results highlight the critical role of thoughtful reward design
in enhancing the tool use capabilities and generalization performance of LLMs.
All the codes are released to facilitate future research.
