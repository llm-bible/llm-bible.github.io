---
layout: publication
title: "Adam-mini: Use Fewer Learning Rates To Gain More"
authors: Zhang Yushun, Chen Congliang, Li Ziniu, Ding Tian, Wu Chenwei, Ye Yinyu, Luo Zhi-quan, Sun Ruoyu
conference: "Arxiv"
year: 2024
bibkey: zhang2024adam
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16793"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We propose Adam-mini an optimizer that achieves on-par or better performance than AdamW with 4537; to 5037; less memory footprint. Adam-mini reduces memory by cutting down the learning rate resources in Adam (i.e. 1/(sqrtv)). We find that (geq) 9037; of these learning rates in v could be harmlessly removed if we (1) carefully partition the parameters into blocks following our proposed principle on Hessian structure; (2) assign a single but good learning rate to each parameter block. We further find that for each of these parameter blocks there exists a single high-quality learning rate that can outperform Adam provided that sufficient resources are available to search it out. We then provide one cost-effective way to find good learning rates and propose Adam-mini. Empirically we verify that Adam-mini performs on par or better than AdamW on various language models sized from 125M to 7B for pre-training supervised fine-tuning and RLHF. The reduced memory footprint of Adam-mini also alleviates communication overheads among GPUs and CPUs thereby increasing throughput. For instance Adam-mini achieves 49.637; higher throughput than AdamW when pre-training Llama2-7B on 2(times) A800-80GB GPUs which saves 3337; wall-clock time for pre-training.
