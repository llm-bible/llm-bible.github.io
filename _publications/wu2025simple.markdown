---
layout: publication
title: 'Openuni: A Simple Baseline For Unified Multimodal Understanding And Generation'
authors: Size Wu, Zhonghua Wu, Zerui Gong, Qingyi Tao, Sheng Jin, Qinyue Li, Wei Li, Chen Change Loy
conference: "Arxiv"
year: 2025
bibkey: wu2025simple
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23661'}
  - {name: "Code", url: 'https://github.com/wusize/OpenUni'}
tags: ['Has Code', 'Transformer', 'Training Techniques', 'Model Architecture', 'Merging', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
In this report, we present OpenUni, a simple, lightweight, and fully open-source baseline for unifying multimodal understanding and generation. Inspired by prevailing practices in unified model learning, we adopt an efficient training strategy that minimizes the training complexity and overhead by bridging the off-the-shelf multimodal large language models (LLMs) and diffusion models through a set of learnable queries and a light-weight transformer-based connector. With a minimalist choice of architecture, we demonstrate that OpenUni can: 1) generate high-quality and instruction-aligned images, and 2) achieve exceptional performance on standard benchmarks such as GenEval, DPG- Bench, and WISE, with only 1.1B and 3.1B activated parameters. To support open research and community advancement, we release all model weights, training code, and our curated training datasets (including 23M image-text pairs) at https://github.com/wusize/OpenUni.
