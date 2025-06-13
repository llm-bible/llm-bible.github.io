---
layout: publication
title: 'Calibrating Language Models With Adaptive Temperature Scaling'
authors: Johnathan Xie, Annie S. Chen, Yoonho Lee, Eric Mitchell, Chelsea Finn
conference: "Arxiv"
year: 2024
bibkey: xie2024calibrating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19817"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training']
---
The effectiveness of large language models (LLMs) is not only measured by
their ability to generate accurate outputs but also by their calibration-how
well their confidence scores reflect the probability of their outputs being
correct. While unsupervised pre-training has been shown to yield LLMs with
well-calibrated conditional probabilities, recent studies have shown that after
fine-tuning with reinforcement learning from human feedback (RLHF), the
calibration of these models degrades significantly. In this work, we introduce
Adaptive Temperature Scaling (ATS), a post-hoc calibration method that predicts
a temperature scaling parameter for each token prediction. The predicted
temperature values adapt based on token-level features and are fit over a
standard supervised fine-tuning (SFT) dataset. The adaptive nature of ATS
addresses the varying degrees of calibration shift that can occur after RLHF
fine-tuning. ATS improves calibration by over 10-50% across three downstream
natural language evaluation benchmarks compared to prior calibration methods
and does not impede performance improvements from RLHF.
