---
layout: publication
title: 'LIFT The Veil For The Truth: Principal Weights Emerge After Rank Reduction For Reasoning-focused Supervised Fine-tuning'
authors: Zihang Liu, Tianyu Pang, Oleg Balabanov, Chaoqun Yang, Tianjin Huang, Lu Yin, Yaoqing Yang, Shiwei Liu
conference: "Arxiv"
year: 2025
bibkey: liu2025lift
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00772"}
  - {name: "Code", url: "https://github.com/zihanghliu/LIFT"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Reinforcement Learning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Recent studies have shown that supervised fine-tuning of LLMs on a small number of high-quality datasets can yield strong reasoning capabilities. However, full fine-tuning (Full FT), while powerful, is computationally expensive and susceptible to overfitting and catastrophic forgetting, particularly when data is limited. Sparse fine-tuning, which previously achieved notable success by updating only a small subset of model parameters, offers a promising trade-off between efficiency and effectiveness. Yet, it has lagged behind in the LLM era due to the difficulty of identifying parameters truly critical for reasoning. In this work, we state that weights with the largest magnitude after low-rank approximation are critical weights for fine-tuning, which we call Principal Weights. Surprisingly, while magnitude-based sparse fine-tuning performs poorly as a baseline on LLM fine-tuning, it becomes highly effective after rank reduction. These insights motivate our method: Low-rank Informed Sparse Fine-Tuning (LIFT). LIFT only updates the top 5% Principal Weights throughout training and consistently achieves better performance on reasoning tasks than Full FT, while maintaining memory efficiency on par with popular parameter-efficient fine-tuning methods. In addition to strong performance on target domains such as arithmetic reasoning, LIFT also retains up to 20% more source-domain knowledge, compared to Full FT and LoRA. Our code is available at: https://github.com/zihanghliu/LIFT.
