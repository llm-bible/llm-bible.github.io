---
layout: publication
title: 'Finegates: Llms Finetuning With Compression Using Stochastic Gates'
authors: Jonathan Svirsky, Yehonathan Refael, Ofir Lindenbaum
conference: "Arxiv"
year: 2024
bibkey: svirsky2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12951"}
tags: ['Applications', 'Reinforcement Learning']
---
Large Language Models (LLMs), with billions of parameters, present
significant challenges for full finetuning due to the high computational
demands, memory requirements, and impracticality of many real-world
applications. When faced with limited computational resources or small
datasets, updating all model parameters can often result in overfitting. To
address this, lightweight finetuning techniques have been proposed, like
learning low-rank adapter layers. These methods aim to train only a few
additional parameters combined with the base model, which remains frozen,
reducing resource usage and mitigating overfitting risks. In this work, we
propose an adaptor model based on stochastic gates that simultaneously sparsify
the frozen base model with task-specific adaptation. Our method comes with a
small number of trainable parameters and allows us to speed up the base model
inference with competitive accuracy. We evaluate it in additional variants by
equipping it with additional low-rank parameters and comparing it to several
recent baselines. Our results show that the proposed method improves the
finetuned model accuracy comparatively to the several baselines and allows the
removal of up to 20-40% without significant accuracy loss.
