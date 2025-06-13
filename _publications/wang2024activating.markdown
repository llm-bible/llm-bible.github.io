---
layout: publication
title: 'Activating Distributed Visual Region Within Llms For Efficient And Effective Vision-language Training And Inference'
authors: Siyuan Wang, Dianyi Wang, Chengxing Zhou, Zejun Li, Zhihao Fan, Xuanjing Huang, Zhongyu Wei
conference: "Arxiv"
year: 2024
bibkey: wang2024activating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12785"}
tags: ['Efficiency and Optimization', 'Pruning', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models']
---
Large Vision-Language Models (LVLMs) typically learn visual capacity through
visual instruction tuning, involving updates to both a projector and their LLM
backbones. Inspired by the concept of a visual region in the human brain, we
investigate the existence of an analogous \textit\{visual region\} within LLMs
that functions as a cognitive core, and explore the potential of efficient
training of LVLMs via selective layers tuning. Using Bunny-Llama-3-8B-V for
detailed analysis and other three LVLMs for validation across diverse visual
and textual tasks, we find that selectively updating 25% of LLMs layers, when
sparsely and uniformly distributed, can preserve nearly 99% of visual
performance and maintain or improve textual task results, while effectively
reducing training time. Based on this targeted training approach, we further
propose a novel visual region-based pruning paradigm, removing non-critical
layers outside the visual region, which can achieve minimal performance loss.
This study offers an effective and efficient strategy for LVLM training and
inference by activating a layer-wise visual region within LLMs, which proves
consistently effective across different models.
