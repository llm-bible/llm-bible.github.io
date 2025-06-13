---
layout: publication
title: 'Harnessing On-device Large Language Model: Empirical Results And Implications For AI PC'
authors: Qingyu Song, Peiyu Liao, Wenqian Zhao, Yiwen Wang, Shoubo Hu, Hui-ling Zhen, Ning Jiang, Mingxuan Yuan
conference: "Arxiv"
year: 2025
bibkey: song2025harnessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15030"}
  - {name: "Code", url: "https://github.com/simmonssong/LLMOnDevice"}
tags: ['Training Techniques', 'Efficiency and Optimization', 'Has Code', 'Quantization']
---
The increasing deployment of Large Language Models (LLMs) on edge devices, driven by model advancements and hardware improvements, offers significant privacy benefits. However, these on-device LLMs inherently face performance limitations due to reduced model capacity and necessary compression techniques. To address this, we introduce a systematic methodology -- encompassing model capability, development efficiency, and system resources -- for evaluating on-device LLMs. Our comprehensive evaluation, encompassing models from 0.5B to 14B parameters and seven post-training quantization (PTQ) methods on commodity laptops, yields several critical insights: 1) System-level metrics exhibit near-linear scaling with effective bits-per-weight (BPW). 2) A practical threshold exists around \\(\sim\\)3.5 effective BPW, larger models subjected to low-bit quantization consistently outperform smaller models utilizing higher bit-precision. 3) Quantization with low BPW incurs marginal accuracy loss but significant memory savings. 4) Determined by low-level implementation specifics power consumption on CPU, where computation-intensive operations spend more power than memory-intensive ones. These findings offer crucial insights and practical guidelines for the efficient deployment and optimized configuration of LLMs on resource-constrained edge devices. Our codebase is available at https://github.com/simmonssong/LLMOnDevice.
