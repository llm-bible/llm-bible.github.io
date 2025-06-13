---
layout: publication
title: 'Diffpo: Diffusion-styled Preference Optimization For Efficient Inference-time Alignment Of Large Language Models'
authors: Ruizhe Chen, Wenhao Chai, Zhifei Yang, Xiaotian Zhang, Joey Tianyi Zhou, Tony Quek, Soujanya Poria, Zuozhu Liu
conference: "Arxiv"
year: 2025
bibkey: chen2025diffusion
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04240'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Merging']
---
Inference-time alignment provides an efficient alternative for aligning LLMs with humans. However, these approaches still face challenges, such as limited scalability due to policy-specific value functions and latency during the inference phase. In this paper, we propose a novel approach, Diffusion-styled Preference Optimization (\model), which provides an efficient and policy-agnostic solution for aligning LLMs with humans. By directly performing alignment at sentence level, \model~avoids the time latency associated with token-level generation. Designed as a plug-and-play module, \model~can be seamlessly integrated with various base models to enhance their alignment. Extensive experiments on AlpacaEval 2, MT-bench, and HH-RLHF demonstrate that \model~achieves superior alignment performance across various settings, achieving a favorable trade-off between alignment quality and inference-time latency. Furthermore, \model~demonstrates model-agnostic scalability, significantly improving the performance of large models such as Llama-3-70B.
