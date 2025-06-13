---
layout: publication
title: 'Can Large Language Models Learn Independent Causal Mechanisms?'
authors: Gaël Gendron, Bao Trung Nguyen, Alex Yuxuan Peng, Michael Witbrock, Gillian Dobbie
conference: "Arxiv"
year: 2024
bibkey: gendron2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02636"}
tags: ['Security', 'Training Techniques', 'Model Architecture', 'Pretraining Methods', 'Fine-Tuning']
---
Despite impressive performance on language modelling and complex reasoning
tasks, Large Language Models (LLMs) fall short on the same tasks in uncommon
settings or with distribution shifts, exhibiting a lack of generalisation
ability. By contrast, systems such as causal models, that learn abstract
variables and causal relationships, can demonstrate increased robustness
against changes in the distribution. One reason for this success is the
existence and use of Independent Causal Mechanisms (ICMs) representing
high-level concepts that only sparsely interact. In this work, we apply two
concepts from causality to learn ICMs within LLMs. We develop a new LLM
architecture composed of multiple sparsely interacting language modelling
modules. We show that such causal constraints can improve out-of-distribution
performance on abstract and causal reasoning tasks. We also investigate the
level of independence and domain specialisation and show that LLMs rely on
pre-trained partially domain-invariant mechanisms resilient to fine-tuning.
