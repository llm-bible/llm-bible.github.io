---
layout: publication
title: 'DIVE: Diversified Iterative Self-improvement'
authors: Yiwei Qin, Yixiu Liu, Pengfei Liu
conference: "Arxiv"
year: 2025
bibkey: qin2025diversified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.00747"}
  - {name: "Code", url: "https://github.com/qinyiwei/DIVE"}
tags: ['Fine-Tuning', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Recent advances in large language models (LLMs) have demonstrated the
effectiveness of Iterative Self-Improvement (ISI) techniques. However,
continuous training on self-generated data leads to reduced output diversity, a
limitation particularly critical in reasoning tasks where diverse solution
paths are essential. We present DIVE (Diversified Iterative Self-Improvement),
a novel framework that addresses this challenge through two key components:
Sample Pool Expansion for broader solution exploration, and Data Selection for
balancing diversity and quality in preference pairs. Experiments on MATH and
GSM8k datasets show that DIVE achieves a 10% to 45% relative increase in output
diversity metrics while maintaining performance quality compared to vanilla
ISI. Our ablation studies confirm both components' significance in achieving
these improvements. Code is available at https://github.com/qinyiwei/DIVE.
