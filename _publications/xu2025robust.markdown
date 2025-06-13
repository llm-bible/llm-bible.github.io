---
layout: publication
title: 'OBLIVIATE: Robust And Practical Machine Unlearning For Large Language Models'
authors: Xiaoyu Xu, Minxin Du, Qingqing Ye, Haibo Hu
conference: "Arxiv"
year: 2025
bibkey: xu2025robust
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04416"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Pretraining Methods', 'Distillation']
---
Large language models (LLMs) trained over extensive corpora risk memorizing
sensitive, copyrighted, or toxic content. To address this, we propose
OBLIVIATE, a robust unlearning framework that removes targeted data while
preserving model utility. The framework follows a structured process:
extracting target tokens, building retain sets, and fine-tuning with a tailored
loss function comprising three components -- masking, distillation, and world
fact. Using low-rank adapters (LoRA), it ensures efficiency without
compromising unlearning quality. We conduct experiments on multiple datasets,
including the Harry Potter series, WMDP, and TOFU, using a comprehensive suite
of metrics: forget quality (new document-level memorization score), model
utility, and fluency. Results demonstrate its effectiveness in resisting
membership inference attacks, minimizing the impact on retained data, and
maintaining robustness across diverse scenarios.
