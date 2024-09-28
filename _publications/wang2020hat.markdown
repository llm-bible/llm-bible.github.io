---
layout: publication
title: HAT Hardware-Aware Transformers for Efficient Natural Language Processing
authors: Wang Hanrui, Wu Zhanghao, Liu Zhijian, Cai Han, Zhu Ligeng, Gan Chuang, Han Song
conference: "Arxiv"
year: 2020
bibkey: wang2020hat
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.14187"}
  - {name: "Code", url: "https://github.com/mit-han-lab/hardware-aware-transformers.git"}
tags: ['Model Architecture', 'Transformer', 'Has Code', 'Arxiv']
---
Transformers are ubiquitous in Natural Language Processing (NLP) tasks but they are difficult to be deployed on hardware due to the intensive computation. To enable low-latency inference on resource-constrained hardware platforms we propose to design Hardware-Aware Transformers (HAT) with neural architecture search. We first construct a large design space with and . Then we train a that covers all candidates in the design space and efficiently produces many with weight sharing. Finally we perform an evolutionary search with a hardware latency constraint to find a specialized dedicated to run fast on the target hardware. Extensive experiments on four machine translation tasks demonstrate that HAT can discover efficient models for different hardware (CPU GPU IoT device). When running WMT14 translation task on Raspberry Pi-4 HAT can achieve times speedup times smaller size over baseline Transformer; times speedup times smaller size over Evolved Transformer with times less search cost and no performance loss. HAT code is https://github.com/mit-han-lab/hardware-aware-transformers.git
