---
layout: publication
title: 'Adavip: Aligning Multi-modal Llms Via Adaptive Vision-enhanced Preference Optimization'
authors: Jinda Lu, Jinghan Li, Yuan Gao, Junkang Wu, Jiancan Wu, Xiang Wang, Xiangnan He
conference: "Arxiv"
year: 2025
bibkey: lu2025aligning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.15619'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Multimodal Models']
---
Preference alignment through Direct Preference Optimization (DPO) has
demonstrated significant effectiveness in aligning multimodal large language
models (MLLMs) with human preferences. However, existing methods focus
primarily on language preferences while neglecting the critical visual context.
In this paper, we propose an Adaptive Vision-enhanced Preference optimization
(AdaViP) that addresses these limitations through two key innovations: (1)
vision-based preference pair construction, which integrates multiple visual
foundation models to strategically remove key visual elements from the image,
enhancing MLLMs' sensitivity to visual details; and (2) adaptive preference
optimization that dynamically balances vision- and language-based preferences
for more accurate alignment. Extensive evaluations across different benchmarks
demonstrate our effectiveness. Notably, our AdaViP-7B achieves 93.7% and 96.4%
reductions in response-level and mentioned-level hallucination respectively on
the Object HalBench, significantly outperforming current state-of-the-art
methods.
