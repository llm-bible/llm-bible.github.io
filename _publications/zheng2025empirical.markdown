---
layout: publication
title: 'An Empirical Study Of Qwen3 Quantization'
authors: Xingyu Zheng, Yuye Li, Haoran Chu, Yue Feng, Xudong Ma, Jie Luo, Jinyang Guo, Haotong Qin, Michele Magno, Xianglong Liu
conference: "Arxiv"
year: 2025
bibkey: zheng2025empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.02214"}
  - {name: "Code", url: "https://github.com/Efficient-ML/Qwen3-Quantization"}
tags: ['Efficiency and Optimization', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Has Code', 'Quantization']
---
The Qwen series has emerged as a leading family of open-source Large Language
Models (LLMs), demonstrating remarkable capabilities in natural language
understanding tasks. With the recent release of Qwen3, which exhibits superior
performance across diverse benchmarks, there is growing interest in deploying
these models efficiently in resource-constrained environments. Low-bit
quantization presents a promising solution, yet its impact on Qwen3's
performance remains underexplored. This study conducts a systematic evaluation
of Qwen3's robustness under various quantization settings, aiming to uncover
both opportunities and challenges in compressing this state-of-the-art model.
We rigorously assess 5 existing classic post-training quantization techniques
applied to Qwen3, spanning bit-widths from 1 to 8 bits, and evaluate their
effectiveness across multiple datasets. Our findings reveal that while Qwen3
maintains competitive performance at moderate bit-widths, it experiences
notable degradation in linguistic tasks under ultra-low precision, underscoring
the persistent hurdles in LLM compression. These results emphasize the need for
further research to mitigate performance loss in extreme quantization
scenarios. We anticipate that this empirical analysis will provide actionable
insights for advancing quantization methods tailored to Qwen3 and future LLMs,
ultimately enhancing their practicality without compromising accuracy. Our
project is released on https://github.com/Efficient-ML/Qwen3-Quantization and
https://huggingface.co/collections/Efficient-ML/qwen3-quantization-68164450decb1c868788cb2b.
