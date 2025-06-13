---
layout: publication
title: 'Specoffload: Unlocking Latent GPU Capacity For LLM Inference On Resource-constrained Devices'
authors: Xiangwen Zhuge, Xu Shen, Zeyu Wang, Fan Dang, Xuan Ding, Danyang Li, Yahui Han, Tianxiang Hao, Zheng Yang
conference: "Arxiv"
year: 2025
bibkey: zhuge2025unlocking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.10259'}
  - {name: "Code", url: 'https://github.com/MobiSense/SpecOffload-public'}
tags: ['Reinforcement Learning', 'Has Code']
---
Efficient LLM inference on resource-constrained devices presents significant challenges in compute and memory utilization. Due to limited GPU memory, existing systems offload model weights to CPU memory, incurring substantial I/O overhead between the CPU and GPU. This leads to two major inefficiencies: (1) GPU cores are underutilized, often remaining idle while waiting for data to be loaded; and (2) GPU memory has low impact on performance, as reducing its capacity has minimal effect on overall throughput.In this paper, we propose SpecOffload, a high-throughput inference engine that embeds speculative decoding into offloading. Our key idea is to unlock latent GPU resources for storing and executing a draft model used for speculative decoding, thus accelerating inference at near-zero additional cost. To support this, we carefully orchestrate the interleaved execution of target and draft models in speculative decoding within the offloading pipeline, and propose a planner to manage tensor placement and select optimal parameters. Compared to the best baseline, SpecOffload improves GPU core utilization by 4.49x and boosts inference throughput by 2.54x. Our code is available at https://github.com/MobiSense/SpecOffload-public .
