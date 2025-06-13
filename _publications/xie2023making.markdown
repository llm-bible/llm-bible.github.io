---
layout: publication
title: 'Making Small Language Models Better Multi-task Learners With Mixture-of-task-adapters'
authors: Yukang Xie, Chengyu Wang, Junbing Yan, Jiyong Zhou, Feiqi Deng, Jun Huang
conference: "Arxiv"
year: 2023
bibkey: xie2023making
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.11042'}
tags: ['Transformer', 'Training Techniques', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Recently, Large Language Models (LLMs) have achieved amazing zero-shot
learning performance over a variety of Natural Language Processing (NLP) tasks,
especially for text generative tasks. Yet, the large size of LLMs often leads
to the high computational cost of model training and online deployment. In our
work, we present ALTER, a system that effectively builds the multi-tAsk
Learners with mixTure-of-task-adaptERs upon small language models (with <1B
parameters) to address multiple NLP tasks simultaneously, capturing the
commonalities and differences between tasks, in order to support
domain-specific applications. Specifically, in ALTER, we propose the
Mixture-of-Task-Adapters (MTA) module as an extension to the transformer
architecture for the underlying model to capture the intra-task and inter-task
knowledge. A two-stage training method is further proposed to optimize the
collaboration between adapters at a small computational cost. Experimental
results over a mixture of NLP tasks show that our proposed MTA architecture and
the two-stage training method achieve good performance. Based on ALTER, we have
also produced MTA-equipped language models for various domains.
