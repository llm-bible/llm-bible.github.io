---
layout: publication
title: 'Controlled Low-rank Adaptation With Subspace Regularization For Continued Training On Large Language Models'
authors: Yuheng Lu, Bingshuo Qian, Caixia Yuan, Huixing Jiang, Xiaojie Wang
conference: "Arxiv"
year: 2024
bibkey: lu2024controlled
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16801"}
tags: ['Training Techniques', 'Fine-Tuning']
---
Large language models (LLMs) exhibit remarkable capabilities in natural
language processing but face catastrophic forgetting when learning new tasks,
where adaptation to a new domain leads to a substantial decline in performance
on previous tasks. In this paper, we propose Controlled LoRA (CLoRA), a
sub-space regularization method on LoRA structure. Aiming to reduce the scale
of output change while introduce minimal constraint on model capacity, CLoRA
imposes constraint on the direction of updating matrix's null space.
Experimental results on one-stage LLM finetuning tasks and continual learning
settings highlight the superority of CLoRA as a effective parameter efficient
finetuning method with catastrophic forgetting mitigating.Further investigation
for model parameters indicates that CLoRA effectively balances the trade-off
between model capacity and degree of forgetting.
