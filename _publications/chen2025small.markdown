---
layout: publication
title: 'Small Aid, Big Leap: Efficient Test-time Adaptation For Vision-language Models With Adaptnet'
authors: Xiao Chen, Jiazhen Huang, Qinting Jiang, Fanding Huang, Xianghua Fu, Jingyan Jiang, Zhi Wang
conference: "Arxiv"
year: 2025
bibkey: chen2025small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.02671"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'RAG', 'Fine-Tuning']
---
Test-time adaptation (TTA) has emerged as a critical technique for enhancing the generalization capability of vision-language models (VLMs) during inference. However, existing approaches often incur substantial computational costs and exhibit poor scalability, primarily due to sample-wise adaptation granularity and reliance on costly auxiliary designs such as data augmentation. To address these limitations, we introduce SAIL (Small Aid, Big Leap), a novel adapter-based TTA framework that leverages a lightweight, learnable AdaptNet to enable efficient and scalable model adaptation. As SAIL's core, a frozen pre-trained VLM collaborates with AdaptNet through a confidence-based interpolation weight, generating robust predictions during inference. These predictions serve as self-supervised targets to align AdaptNet's outputs through efficient batch-wise processing, dramatically reducing computational costs without modifying the VLM or requiring memory caches. To mitigate catastrophic forgetting during continual adaptation, we propose a gradient-aware reset strategy driven by a gradient drift indicator (GDI), which dynamically detects domain transitions and strategically resets AdaptNet for stable adaptation. Extensive experiments across diverse benchmarks on two scenarios demonstrate that SAIL achieves state-of-the-art performance while maintaining low computational costs. These results highlight SAIL's effectiveness, efficiency and scalability for real-world deployment. The code will be released upon acceptance.
