---
layout: publication
title: 'Scalable Parameter And Memory Efficient Pretraining For LLM: Recent Algorithmic Advances And Benchmarking'
authors: Athanasios Glentis, Jiaxiang Li, Qiulin Shang, Andi Han, Ioannis Tsaknakis, Quan Wei, Mingyi Hong
conference: "Arxiv"
year: 2025
bibkey: glentis2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.22922"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Survey Paper', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training']
---
Fueled by their remarkable ability to tackle diverse tasks across multiple domains, large language models (LLMs) have grown at an unprecedented rate, with some recent models containing trillions of parameters. This growth is accompanied by substantial computational challenges, particularly regarding the memory and compute resources required for training and fine-tuning. Numerous approaches have been explored to address these issues, such as LoRA. While these methods are effective for fine-tuning, their application to pre-training is significantly more challenging due to the need to learn vast datasets. Motivated by this issue, we aim to address the following questions: Can parameter- or memory-efficient methods enhance pre-training efficiency while achieving performance comparable to full-model training? How can the performance gap be narrowed? To this end, the contributions of this work are the following. (1) We begin by conducting a comprehensive survey that summarizes state-of-the-art methods for efficient pre-training. (2) We perform a benchmark evaluation of several representative memory efficient pre-training approaches to comprehensively evaluate their performance across model sizes. We observe that with a proper choice of optimizer and hyperparameters, full-rank training delivers the best performance, as expected. We also notice that incorporating high-rank updates in low-rank approaches is the key to improving their performance. (3) Finally, we propose two practical techniques, namely weight refactorization and momentum reset, to enhance the performance of efficient pre-training methods. We observe that applying these techniques to the low-rank method (on a 1B model) can achieve a lower perplexity than popular memory efficient algorithms such as GaLore and Fira, while simultaneously using about 25% less memory.
