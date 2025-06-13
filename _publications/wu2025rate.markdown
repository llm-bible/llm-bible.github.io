---
layout: publication
title: 'Backslash: Rate Constrained Optimized Training Of Large Language Models'
authors: Jun Wu, Jiangtao Wen, Yuxing Han
conference: "Arxiv"
year: 2025
bibkey: wu2025rate
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.16968'}
tags: ['Efficiency and Optimization', 'Security', 'Training Techniques', 'Model Architecture', 'Tools', 'Pruning']
---
The rapid advancement of large-language models (LLMs) has driven extensive research into parameter compression after training has been completed, yet compression during the training phase remains largely unexplored. In this work, we introduce Rate-Constrained Training (BackSlash), a novel training-time compression approach based on rate-distortion optimization (RDO). BackSlash enables a flexible trade-off between model accuracy and complexity, significantly reducing parameter redundancy while preserving performance. Experiments in various architectures and tasks demonstrate that BackSlash can reduce memory usage by 60% - 90% without accuracy loss and provides significant compression gain compared to compression after training. Moreover, BackSlash proves to be highly versatile: it enhances generalization with small Lagrange multipliers, improves model robustness to pruning (maintaining accuracy even at 80% pruning rates), and enables network simplification for accelerated inference on edge devices.
