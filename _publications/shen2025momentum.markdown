---
layout: publication
title: 'Mlorc: Momentum Low-rank Compression For Large Language Model Adaptation'
authors: Wei Shen, Zhang Yaxiang, Minhui Huang, Mengfan Xu, Jiawei Zhang, Cong Shen
conference: "Arxiv"
year: 2025
bibkey: shen2025momentum
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01897"}
tags: ['Pretraining Methods', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning']
---
With increasing size of large language models (LLMs), full-parameter fine-tuning imposes substantial memory demands. To alleviate this, we propose a novel memory-efficient training paradigm called Momentum Low-rank compression (MLorc). By directly compressing and reconstructing momentum rather than gradients, MLorc avoids imposing a fixed-rank constraint on weight update matrices and better preserves the training dynamics of full-parameter fine-tuning, in contrast to existing low-rank approaches such as LoRA and GaLore. Empirically, MLorc consistently outperforms other memory-efficient training methods, matches or even exceeds the performance of full fine-tuning with a small rank (e.g., \\(r=4\\)), and generalizes well across different optimizers -- all while not compromising time or memory efficiency. Furthermore, we provide a theoretical guarantee for its convergence under reasonable assumptions.
