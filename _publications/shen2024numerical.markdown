---
layout: publication
title: 'Numerical Pruning For Efficient Autoregressive Models'
authors: Xuan Shen, Zhao Song, Yufa Zhou, Bo Chen, Jing Liu, Ruiyi Zhang, Ryan A. Rossi, Hao Tan, Tong Yu, Xiang Chen, Yufan Zhou, Tong Sun, Pu Zhao, Yanzhi Wang, Jiuxiang Gu
conference: "Arxiv"
year: 2024
bibkey: shen2024numerical
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12441'}
tags: ['Attention Mechanism', 'Language Modeling', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'GPT', 'Pruning', 'Reinforcement Learning', 'Pretraining Methods']
---
Transformers have emerged as the leading architecture in deep learning,
proving to be versatile and highly effective across diverse domains beyond
language and image processing. However, their impressive performance often
incurs high computational costs due to their substantial model size. This paper
focuses on compressing decoder-only transformer-based autoregressive models
through structural weight pruning to improve the model efficiency while
preserving performance for both language and image generation tasks.
Specifically, we propose a training-free pruning method that calculates a
numerical score with Newton's method for the Attention and MLP modules,
respectively. Besides, we further propose another compensation algorithm to
recover the pruned model for better performance. To verify the effectiveness of
our method, we provide both theoretical support and extensive experiments. Our
experiments show that our method achieves state-of-the-art performance with
reduced memory usage and faster generation speeds on GPUs.
