---
layout: publication
title: 'Efficient RLHF: Reducing The Memory Usage Of PPO'
authors: Michael Santacroce, Yadong Lu, Han Yu, Yuanzhi Li, Yelong Shen
conference: "Arxiv"
year: 2023
bibkey: santacroce2023efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.00754'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Reinforcement Learning with Human Feedback (RLHF) has revolutionized language
modeling by aligning models with human preferences. However, the RL stage,
Proximal Policy Optimization (PPO), requires over 3x the memory of Supervised
Fine-Tuning (SFT), making it infeasible to use for most practitioners. To
address this issue, we present a comprehensive analysis the memory usage,
performance, and training time of memory-savings techniques for PPO. We
introduce Hydra-RLHF by first integrating the SFT and Reward models and then
dynamically turning LoRA "off" during training. Our experiments show: 1. Using
LoRA during PPO reduces its memory usage to be smaller than SFT while improving
alignment across four public benchmarks, and 2. Hydra-PPO reduces the latency
per sample of LoRA-PPO by up to 65% while maintaining its performance. Our
results demonstrate that Hydra-PPO is a simple and promising solution for
enabling more widespread usage of RLHF.
