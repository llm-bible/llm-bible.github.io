---
layout: publication
title: Efficient RLHF Reducing The Memory Usage Of PPO
authors: Santacroce Michael, Lu Yadong, Yu Han, Li Yuanzhi, Shen Yelong
conference: "Arxiv"
year: 2023
bibkey: santacroce2023efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.00754"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Language Modeling', 'Reinforcement Learning', 'Training Techniques']
---
Reinforcement Learning with Human Feedback (RLHF) has revolutionized language modeling by aligning models with human preferences. However the RL stage Proximal Policy Optimization (PPO) requires over 3x the memory of Supervised Fine45;Tuning (SFT) making it infeasible to use for most practitioners. To address this issue we present a comprehensive analysis the memory usage performance and training time of memory45;savings techniques for PPO. We introduce Hydra45;RLHF by first integrating the SFT and Reward models and then dynamically turning LoRA off during training. Our experiments show 1. Using LoRA during PPO reduces its memory usage to be smaller than SFT while improving alignment across four public benchmarks and 2. Hydra45;PPO reduces the latency per sample of LoRA45;PPO by up to 6537; while maintaining its performance. Our results demonstrate that Hydra45;PPO is a simple and promising solution for enabling more widespread usage of RLHF.
