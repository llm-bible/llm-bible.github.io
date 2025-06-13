---
layout: publication
title: 'SPAM: Spike-aware Adam With Momentum Reset For Stable LLM Training'
authors: Tianjin Huang, Ziquan Zhu, Gaojie Jin, Lu Liu, Zhangyang Wang, Shiwei Liu
conference: "Arxiv"
year: 2025
bibkey: huang2025spike
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.06842'}
  - {name: "Code", url: 'https://github.com/TianjinYellow/SPAM-Optimizer.git'}
tags: ['Agentic', 'Has Code', 'Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Large Language Models (LLMs) have demonstrated exceptional performance across
diverse tasks, yet their training remains highly resource-intensive and
susceptible to critical challenges such as training instability. A predominant
source of this instability stems from gradient and loss spikes, which disrupt
the learning process, often leading to costly interventions like checkpoint
recovery and experiment restarts, further amplifying inefficiencies. This paper
presents a comprehensive investigation into gradient spikes observed during LLM
training, revealing their prevalence across multiple architectures and
datasets. Our analysis shows that these spikes can be up to \\(1000\times\\) larger
than typical gradients, substantially deteriorating model performance. To
address this issue, we propose Spike-Aware Adam with Momentum Reset SPAM, a
novel optimizer designed to counteract gradient spikes through momentum reset
and spike-aware gradient clipping. Extensive experiments, including both
pre-training and fine-tuning, demonstrate that SPAM consistently surpasses Adam
and its variants across various tasks, including (1) LLM pre-training from 60M
to 1B, (2) 4-bit LLM pre-training,(3) reinforcement learning, and (4) Time
Series Forecasting. Additionally, SPAM facilitates memory-efficient training by
enabling sparse momentum, where only a subset of momentum terms are maintained
and updated. When operating under memory constraints, SPAM outperforms
state-of-the-art memory-efficient optimizers such as GaLore and Adam-Mini. Our
work underscores the importance of mitigating gradient spikes in LLM training
and introduces an effective optimization strategy that enhances both training
stability and resource efficiency at scale. Code is available at
https://github.com/TianjinYellow/SPAM-Optimizer.git
