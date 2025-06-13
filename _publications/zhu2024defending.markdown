---
layout: publication
title: 'Flipguard: Defending Preference Alignment Against Update Regression With Constrained Optimization'
authors: Mingye Zhu, Yi Liu, Quan Wang, Junbo Guo, Zhendong Mao
conference: "Arxiv"
year: 2024
bibkey: zhu2024defending
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.00508'}
tags: ['Attention Mechanism', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent breakthroughs in preference alignment have significantly improved
Large Language Models' ability to generate texts that align with human
preferences and values. However, current alignment metrics typically emphasize
the post-hoc overall improvement, while overlooking a critical aspect:
regression, which refers to the backsliding on previously correctly-handled
data after updates. This potential pitfall may arise from excessive fine-tuning
on already well-aligned data, which subsequently leads to over-alignment and
degeneration. To address this challenge, we propose FlipGuard, a constrained
optimization approach to detect and mitigate update regression with focal
attention. Specifically, FlipGuard identifies performance degradation using a
customized reward characterization and strategically enforces a constraint to
encourage conditional congruence with the pre-aligned model during training.
Comprehensive experiments demonstrate that FlipGuard effectively alleviates
update regression while demonstrating excellent overall performance, with the
added benefit of knowledge preservation while aligning preferences.
