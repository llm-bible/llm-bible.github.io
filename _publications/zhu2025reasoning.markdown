---
layout: publication
title: 'Reasoning-to-defend: Safety-aware Reasoning Can Defend Large Language Models From Jailbreaking'
authors: Junda Zhu, Lingyong Yan, Shuaiqiang Wang, Dawei Yin, Lei Sha
conference: "Arxiv"
year: 2025
bibkey: zhu2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12970"}
tags: ['Responsible AI', 'Security', 'Training Techniques', 'Efficiency and Optimization']
---
Large Reasoning Models (LRMs) have demonstrated impressive performances across diverse domains. However, how safety of Large Language Models (LLMs) benefits from enhanced reasoning capabilities against jailbreak queries remains unexplored. To bridge this gap, in this paper, we propose Reasoning-to-Defend (R2D), a novel training paradigm that integrates a safety-aware reasoning mechanism into LLMs' generation. This enables self-evaluation at each step of the reasoning process, forming safety pivot tokens as indicators of the safety status of responses. Furthermore, in order to improve the accuracy of predicting pivot tokens, we propose Contrastive Pivot Optimization (CPO), which enhances the model's perception of the safety status of given dialogues. LLMs dynamically adjust their response strategies during reasoning, significantly enhancing their safety capabilities defending jailbreak attacks. Extensive experiments demonstrate that R2D effectively mitigates various attacks and improves overall safety, while maintaining the original performances. This highlights the substantial potential of safety-aware reasoning in improving robustness of LRMs and LLMs against various jailbreaks.
