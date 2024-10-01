---
layout: publication
title: 'Less Is More: Data Value Estimation For Visual Instruction Tuning'
authors: Liu Zikang, Zhou Kun, Zhao Wayne Xin, Gao Dawei, Li Yaliang, Wen Ji-rong
conference: "Arxiv"
year: 2024
bibkey: liu2024less
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09559"}
tags: ['Multimodal Models', 'Training Techniques']
---
Visual instruction tuning is the key to building multimodal large language models (MLLMs), which greatly improves the reasoning capabilities of large language models (LLMs) in vision scenario. However, existing MLLMs mostly rely on a mixture of multiple highly diverse visual instruction datasets for training (even more than a million instructions), which may introduce data redundancy. To investigate this issue, we conduct a series of empirical studies, which reveal a significant redundancy within the visual instruction datasets, and show that greatly reducing the amount of several instruction dataset even do not affect the performance. Based on the findings, we propose a new data selection approach TIVE, to eliminate redundancy within visual instruction data. TIVE first estimates the task-level and instance-level value of the visual instructions based on computed gradients. Then, according to the estimated values, TIVE determines the task proportion within the visual instructions, and selects representative instances to compose a smaller visual instruction subset for training. Experiments on LLaVA-1.5 show that our approach using only about 7.5&#37; data can achieve comparable performance as the full-data fine-tuned model across seven benchmarks, even surpassing it on four of the benchmarks. Our code and data will be publicly released.
