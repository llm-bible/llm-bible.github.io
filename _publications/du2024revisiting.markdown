---
layout: publication
title: 'Revisiting Moe And Dense Speed-accuracy Comparisons For LLM Training'
authors: Du Xianzhi, Gunter Tom, Kong Xiang, Lee Mark, Wang Zirui, Zhang Aonan, Du Nan, Pang Ruoming
conference: "Arxiv"
year: 2024
bibkey: du2024revisiting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15052"}
  - {name: "Code", url: "https://github.com/apple/axlearn"}
tags: ['Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Mixture-of-Experts (MoE) enjoys performance gain by increasing model capacity while keeping computation cost constant. When comparing MoE to dense models, prior work typically adopt the following setting: 1) use FLOPs or activated parameters as a measure of model complexity; 2) train all models to the same number of tokens. We argue that this setting favors MoE as FLOPs and activated parameters do not accurately measure the communication overhead in sparse layers, leading to a larger actual training budget for MoE. In this work, we revisit the settings by adopting step time as a more accurate measure of model complexity, and by determining the total compute budget under the Chinchilla compute-optimal settings. To efficiently run MoE on modern accelerators, we adopt a 3D sharding method that keeps the dense-to-MoE step time increase within a healthy range. We evaluate MoE and dense LLMs on a set of nine 0-shot and two 1-shot English tasks, as well as MMLU 5-shot and GSM8K 8-shot across three model scales at 6.4B, 12.6B, and 29.6B. Experimental results show that even under these settings, MoE consistently outperform dense LLMs on the speed-accuracy trade-off curve with meaningful gaps. Our full model implementation and sharding strategy has been released at~\url\{https://github.com/apple/axlearn\}
