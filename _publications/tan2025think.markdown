---
layout: publication
title: 'Think Twice, Act Once: Token-aware Compression And Action Reuse For Efficient Inference In Vision-language-action Models'
authors: Xudong Tan, Yaoxin Yang, Peng Ye, Jialin Zheng, Bizhe Bai, Xinyi Wang, Jia Hao, Tao Chen
conference: "Arxiv"
year: 2025
bibkey: tan2025think
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.21200'}
tags: ['Efficiency and Optimization', 'GPT', 'Applications', 'Training Techniques', 'Tools', 'Multimodal Models', 'Pretraining Methods']
---
Vision-Language-Action (VLA) models have emerged as a powerful paradigm for general-purpose robot control through natural language instructions. However, their high inference cost-stemming from large-scale token computation and autoregressive decoding-poses significant challenges for real-time deployment and edge applications. While prior work has primarily focused on architectural optimization, we take a different perspective by identifying a dual form of redundancy in VLA models: (i) high similarity across consecutive action steps, and (ii) substantial redundancy in visual tokens. Motivated by these observations, we propose FlashVLA, the first training-free and plug-and-play acceleration framework that enables action reuse in VLA models. FlashVLA improves inference efficiency through a token-aware action reuse mechanism that avoids redundant decoding across stable action steps, and an information-guided visual token selection strategy that prunes low-contribution tokens. Extensive experiments on the LIBERO benchmark show that FlashVLA reduces FLOPs by 55.7% and latency by 36.0%, with only a 0.7% drop in task success rate. These results demonstrate the effectiveness of FlashVLA in enabling lightweight, low-latency VLA inference without retraining.
