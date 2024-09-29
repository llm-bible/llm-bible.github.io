---
layout: publication
title: Visual Prompt Tuning For Test45;time Domain Adaptation
authors: Gao Yunhe, Shi Xingjian, Zhu Yi, Wang Hao, Tang Zhiqiang, Zhou Xiong, Li Mu, Metaxas Dimitris N.
conference: "Arxiv"
year: 2022
bibkey: gao2022visual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.04831"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Models should be able to adapt to unseen data during test45;time to avoid performance drops caused by inevitable distribution shifts in real45;world deployment scenarios. In this work we tackle the practical yet challenging test45;time adaptation (TTA) problem where a model adapts to the target domain without accessing the source data. We propose a simple recipe called textit123;Data45;efficient Prompt Tuning125; (DePT) with two key ingredients. First DePT plugs visual prompts into the vision Transformer and only tunes these source45;initialized prompts during adaptation. We find such parameter45;efficient finetuning can efficiently adapt the model representation to the target domain without overfitting to the noise in the learning objective. Second DePT bootstraps the source representation to the target domain by memory bank45;based online pseudo45;labeling. A hierarchical self45;supervised regularization specially designed for prompts is jointly optimized to alleviate error accumulation during self45;training. With much fewer tunable parameters DePT demonstrates not only state45;of45;the45;art performance on major adaptation benchmarks VisDA45;C ImageNet45;C and DomainNet45;126 but also superior data efficiency i.e. adaptation with only 137; or 1037; data without much performance degradation compared to 10037; data. In addition DePT is also versatile to be extended to online or multi45;source TTA settings.
