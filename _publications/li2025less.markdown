---
layout: publication
title: 'LIMR: Less Is More For RL Scaling'
authors: Xuefeng Li, Haoyang Zou, Pengfei Liu
conference: "Arxiv"
year: 2025
bibkey: li2025less
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.11886'}
  - {name: "Code", url: 'https://github.com/GAIR-NLP/LIMR'}
tags: ['Has Code', 'Efficiency and Optimization', 'Distillation', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability', 'Pretraining Methods']
---
In this paper, we ask: what truly determines the effectiveness of RL training
data for enhancing language models' reasoning capabilities? While recent
advances like o1, Deepseek R1, and Kimi1.5 demonstrate RL's potential, the lack
of transparency about training data requirements has hindered systematic
progress. Starting directly from base models without distillation, we challenge
the assumption that scaling up RL training data inherently improves
performance. we demonstrate that a strategically selected subset of just 1,389
samples can outperform the full 8,523-sample dataset. We introduce Learning
Impact Measurement (LIM), an automated method to evaluate and prioritize
training samples based on their alignment with model learning trajectories,
enabling efficient resource utilization and scalable implementation. Our method
achieves comparable or even superior performance using only 1,389 samples
versus the full 8,523 samples dataset. Notably, while recent data-efficient
approaches (e.g., LIMO and s1) show promise with 32B-scale models, we find it
significantly underperforms at 7B-scale through supervised fine-tuning (SFT).
In contrast, our RL-based LIMR achieves 16.7% higher accuracy on AIME24 and
outperforms LIMO and s1 by 13.0% and 22.2% on MATH500. These results
fundamentally reshape our understanding of RL scaling in LLMs, demonstrating
that precise sample selection, rather than data scale, may be the key to
unlocking enhanced reasoning capabilities. For reproducible research and future
innovation, we are open-sourcing LIMR, including implementation of LIM,
training and evaluation code, curated datasets, and trained models at
https://github.com/GAIR-NLP/LIMR.
