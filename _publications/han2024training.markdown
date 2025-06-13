---
layout: publication
title: 'Filter, Correlate, Compress: Training-free Token Reduction For MLLM Acceleration'
authors: Yuhang Han, Xuyang Liu, Zihan Zhang, Pengxiang Ding, Donglin Wang, Honggang Chen, Qingsen Yan, Siteng Huang
conference: "Arxiv"
year: 2024
bibkey: han2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17686"}
  - {name: "Code", url: "https://ficoco-accelerate.github.io/"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Merging', 'Has Code']
---
The quadratic complexity of Multimodal Large Language Models (MLLMs) with
respect to sequence length poses significant computational and memory
challenges, hindering their real-world deployment. While existing training-free
token reduction methods aim to address these inefficiencies, how to precisely
identify redundant visual tokens and recover the essential information from the
discarded tokens remain unclear. In this paper, we propose a
''filter-correlate-compress'' framework that decomposes the token reduction
into three stages: filtering redundant tokens, correlating discarded
information to preserved tokens, and compressing tokens to minimize redundancy.
Following the framework, we propose a solution FiCoCo to identify limitations
in single redundancy assessment, propose adaptive strategies to retain critical
information from discarded tokens, and mitigate semantic dilution during token
fusion. Two specialized variants, FiCoCo-V (for vision encoders) and FiCoCo-L
(for LLM decoders), further optimize efficiency across MLLM architectures.
Extensive experiments demonstrate that FiCoCo achieves up to 5.7x/14.7x FLOPs
reduction with 92.8%/93.6% performance retention on LLaVA-1.5-7B/LLaVA-NeXT-7B.
Our methods consistently outperform state-of-the-art training-free approaches,
showcasing effectiveness and generalizability across model architectures,
sizes, and tasks without requiring retraining. Our project page is at
https://ficoco-accelerate.github.io/.
