---
layout: publication
title: Online Merging Optimizers For Boosting Rewards And Mitigating Tax In Alignment
authors: Lu Keming, Yu Bowen, Huang Fei, Fan Yang, Lin Runji, Zhou Chang
conference: "Arxiv"
year: 2024
bibkey: lu2024online
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.17931"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Merging', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Effectively aligning Large Language Models (LLMs) with human-centric values while preventing the degradation of abilities acquired through Pre-training and Supervised Fine-tuning (SFT) poses a central challenge in Reinforcement Learning from Human Feedback (RLHF). In this paper we first discover that interpolating RLHF and SFT model parameters can adjust the trade-off between human preference and basic capabilities thereby reducing the alignment tax at the cost of alignment reward. Inspired by this we propose integrating the RL policy and SFT models at each optimization step in RLHF to continuously regulate the training direction introducing the Online Merging Optimizer. Specifically we merge gradients with the parameter differences between SFT and pretrained models effectively steering the gradient towards maximizing rewards in the direction of SFT optimization. We demonstrate that our optimizer works well with different LLM families such as Qwen and LLaMA across various model sizes ranging from 1.8B to 8B various RLHF algorithms like DPO and KTO and existing model merging methods. It significantly enhances alignment reward while mitigating alignment tax achieving higher overall performance across 14 benchmarks.
