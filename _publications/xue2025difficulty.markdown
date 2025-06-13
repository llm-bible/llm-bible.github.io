---
layout: publication
title: 'DAST: Difficulty-aware Self-training On Large Language Models'
authors: Boyang Xue, Qi Zhu, Hongru Wang, Rui Wang, Sheng Wang, Hongling Xu, Fei Mi, Yasheng Wang, Lifeng Shang, Qun Liu, Kam-fai Wong
conference: "Arxiv"
year: 2025
bibkey: xue2025difficulty
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.09029"}
tags: ['Training Techniques', 'Fine-Tuning', 'Tools', 'Reinforcement Learning']
---
Present Large Language Models (LLM) self-training methods always under-sample
on challenging queries, leading to inadequate learning on difficult problems
which limits LLMs' ability. Therefore, this work proposes a difficulty-aware
self-training (DAST) framework that focuses on improving both the quantity and
quality of self-generated responses on challenging queries during
self-training. DAST is specified in three components: 1) sampling-based
difficulty level estimation, 2) difficulty-aware data augmentation, and 3) the
self-training algorithm using SFT and DPO respectively. Experiments on
mathematical tasks demonstrate the effectiveness and generalization of DAST,
highlighting the critical role of difficulty-aware strategies in advancing LLM
self-training.
