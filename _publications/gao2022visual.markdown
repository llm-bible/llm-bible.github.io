---
layout: publication
title: 'Visual Prompt Tuning For Test-time Domain Adaptation'
authors: Gao Yunhe, Shi Xingjian, Zhu Yi, Wang Hao, Tang Zhiqiang, Zhou Xiong, Li Mu, Metaxas Dimitris N.
conference: "Arxiv"
year: 2022
bibkey: gao2022visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.04831"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Models should be able to adapt to unseen data during test-time to avoid
performance drops caused by inevitable distribution shifts in real-world
deployment scenarios. In this work, we tackle the practical yet challenging
test-time adaptation (TTA) problem, where a model adapts to the target domain
without accessing the source data. We propose a simple recipe called
\textit\{Data-efficient Prompt Tuning\} (DePT) with two key ingredients. First,
DePT plugs visual prompts into the vision Transformer and only tunes these
source-initialized prompts during adaptation. We find such parameter-efficient
finetuning can efficiently adapt the model representation to the target domain
without overfitting to the noise in the learning objective. Second, DePT
bootstraps the source representation to the target domain by memory bank-based
online pseudo-labeling. A hierarchical self-supervised regularization specially
designed for prompts is jointly optimized to alleviate error accumulation
during self-training. With much fewer tunable parameters, DePT demonstrates not
only state-of-the-art performance on major adaptation benchmarks VisDA-C,
ImageNet-C, and DomainNet-126, but also superior data efficiency, i.e.,
adaptation with only 1\% or 10\% data without much performance degradation
compared to 100\% data. In addition, DePT is also versatile to be extended to
online or multi-source TTA settings.
