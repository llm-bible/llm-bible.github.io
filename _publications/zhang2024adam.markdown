---
layout: publication
title: Adam45;mini Use Fewer Learning Rates To Gain More
authors: Zhang Yushun, Chen Congliang, Li Ziniu, Ding Tian, Wu Chenwei, Ye Yinyu, Luo Zhi-quan, Sun Ruoyu
conference: "Arxiv"
year: 2024
bibkey: zhang2024adam
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16793"}
tags: ['Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
We propose Adam45;mini an optimizer that achieves on45;par or better performance than AdamW with 4537; to 5037; less memory footprint. Adam45;mini reduces memory by cutting down the learning rate resources in Adam (i.e. 1/sqrt123;v125;). We find that ≥ 9037; of these learning rates in v could be harmlessly removed if we (1) carefully partition the parameters into blocks following our proposed principle on Hessian structure; (2) assign a single but good learning rate to each parameter block. We further find that for each of these parameter blocks there exists a single high45;quality learning rate that can outperform Adam provided that sufficient resources are available to search it out. We then provide one cost45;effective way to find good learning rates and propose Adam45;mini. Empirically we verify that Adam45;mini performs on par or better than AdamW on various language models sized from 125M to 7B for pre45;training supervised fine45;tuning and RLHF. The reduced memory footprint of Adam45;mini also alleviates communication overheads among GPUs and CPUs thereby increasing throughput. For instance Adam45;mini achieves 49.637; higher throughput than AdamW when pre45;training Llama245;7B on 2× A80045;80GB GPUs which saves 3337; wall45;clock time for pre45;training.
