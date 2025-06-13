---
layout: publication
title: 'Rankadaptor: Hierarchical Rank Allocation For Efficient Fine-tuning Pruned Llms Via Performance Model'
authors: Changhai Zhou, Shijie Han, Lining Yang, Yuhua Zhou, Xu Cheng, Yibin Wang, Hongguang Li
conference: "Arxiv"
year: 2024
bibkey: zhou2024hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15734"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Pruning', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
The efficient compression of large language models (LLMs) has become
increasingly popular. However, recovering the performance of compressed LLMs
remains a major challenge. The current practice in LLM compression entails the
implementation of structural pruning, complemented by a recovery phase that
leverages the Low-Rank Adaptation (LoRA) algorithm. Structural pruning's uneven
modification of model architecture, coupled with standard LoRA's fixed
configuration allocation across layers in an online pipeline, leads to
suboptimal performance in various downstream tasks for pruned models. To
address this challenge, we introduce RankAdaptor, a hierarchical rank
allocation method that enables efficient fine-tuning of pruned LLMs according
to layerwise specific recovery requirements. We employ a performance model that
conducts offline meta-learning and online incremental learning to explore
optimal rank values for each layer. Comprehensive experiments on popular
benchmarks show that RankAdaptor consistently outperforms state-of-the-art
methods across a variety of pruning settings and LLM architectures, with
improvements ranging from 0.7% to 5.5%.
