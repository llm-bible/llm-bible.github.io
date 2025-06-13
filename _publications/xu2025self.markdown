---
layout: publication
title: 'Self-ensemble: Mitigating Confidence Distortion For Large Language Models'
authors: Zicheng Xu, Guanchu Wang, Guangyao Zheng, Yu-neng Chuang, Alexander Szalay, Xia Hu, Vladimir Braverman
conference: "Arxiv"
year: 2025
bibkey: xu2025self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01951"}
tags: ['Attention Mechanism', 'Merging', 'Model Architecture', 'Reinforcement Learning']
---
Although Large Language Models (LLMs) perform well in general fields, they exhibit a confidence distortion problem on multi-choice question-answering (MCQA), particularly as the number of answer choices increases. Specifically, on MCQA with many choices, LLMs suffer from under-confidence in correct predictions and over-confidence in incorrect ones, leading to a substantially degraded performance. To solve this problem, we propose Self-ensemble in this work. Our method splits the choices into several groups and ensembles LLM predictions across these groups to reach a final decision. The advantage of Self-ensemble is its plug-and-play nature, where it can be integrated into existing LLM architecture based on a designed attention mask and positional encoding, without requiring labeled datasets for parameter tuning. Experimental results on three LLMs and datasets demonstrate that Self-ensemble comprehensively addresses the confidence distortion problem of LLMs, outperforming standard inference as well as baseline methods.
