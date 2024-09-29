---
layout: publication
title: Mixlora Enhancing Large Language Models Fine-tuning With Lora-based Mixture Of Experts
authors: Li Dengchun, Ma Yingzi, Wang Naizheng, Ye Zhengmao, Cheng Zhiyuan, Tang Yinghao, Zhang Yan, Duan Lei, Zuo Jie, Yang Cal, Tang Mingjie
conference: "Arxiv"
year: 2024
bibkey: li2024mixlora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.15159"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Fine-tuning Large Language Models (LLMs) is a common practice to adapt pre-trained models for specific applications. While methods like LoRA have effectively addressed GPU memory constraints during fine-tuning their performance often falls short especially in multi-task scenarios. In contrast Mixture-of-Expert (MoE) models such as Mixtral 8x7B demonstrate remarkable performance in multi-task learning scenarios while maintaining a reduced parameter count. However the resource requirements of these MoEs remain challenging particularly for consumer-grade GPUs with less than 24GB memory. To tackle these challenges we propose MixLoRA an approach to construct a resource-efficient sparse MoE model based on LoRA. MixLoRA inserts multiple LoRA-based experts within the feed-forward network block of a frozen pre-trained dense model and employs a commonly used top-k router. Unlike other LoRA-based MoE methods MixLoRA enhances model performance by utilizing independent attention-layer LoRA adapters. Additionally an auxiliary load balance loss is employed to address the imbalance problem of the router. Our evaluations show that MixLoRA improves about 937; accuracy compared to state-of-the-art PEFT methods in multi-task learning scenarios. We also propose a new high-throughput framework to alleviate the computation and memory bottlenecks during the training and inference of MOE models. This framework reduces GPU memory consumption by 4037; and token computation latency by 3037; during both training and inference.
