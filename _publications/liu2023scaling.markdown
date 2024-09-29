---
layout: publication
title: Scaling Laws Of Rope-based Extrapolation
authors: Liu Xiaoran, Yan Hang, Zhang Shuo, An Chenxin, Qiu Xipeng, Lin Dahua
conference: "Arxiv"
year: 2023
bibkey: liu2023scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05209"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Scaling Laws', 'Tools', 'Training Techniques']
---
The extrapolation capability of Large Language Models (LLMs) based on Rotary Position Embedding is currently a topic of considerable interest. The mainstream approach to addressing extrapolation with LLMs involves modifying RoPE by replacing 10000 the rotary base of θ_n=10000^-2n/d in the original RoPE with a larger value and providing longer fine-tuning text. In this work we first observe that fine-tuning a RoPE-based LLM with either a smaller or larger base in pre-training context length could significantly enhance its extrapolation performance. After that we propose a unified framework from the periodic perspective to describe the relationship between the extrapolation performance and base value as well as tuning context length. In this process we also explain the origin of the RoPE-based extrapolation issue by . Besides these observations and analyses we achieve extrapolation up to 1 million context length within only 16K training length on LLaMA2 7B and 13B.
