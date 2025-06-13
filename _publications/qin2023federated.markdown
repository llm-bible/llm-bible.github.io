---
layout: publication
title: 'Federated Full-parameter Tuning Of Billion-sized Language Models With Communication Cost Under 18 Kilobytes'
authors: Zhen Qin, Daoyuan Chen, Bingchen Qian, Bolin Ding, Yaliang Li, Shuiguang Deng
conference: "Arxiv"
year: 2023
bibkey: qin2023federated
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.06353"}
tags: ['Pretraining Methods', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning']
---
Pre-trained large language models (LLMs) need fine-tuning to improve their
responsiveness to natural language instructions. Federated learning offers a
way to fine-tune LLMs using the abundant data on end devices without
compromising data privacy. Most existing federated fine-tuning methods for LLMs
rely on parameter-efficient fine-tuning techniques, which may not reach the
performance height possible with full-parameter tuning. However, federated
full-parameter tuning of LLMs is a non-trivial problem due to the immense
communication cost. This work introduces FedKSeed that employs zeroth-order
optimization with a finite set of random seeds. It significantly reduces
transmission requirements between the server and clients to just a few random
seeds and scalar gradients, amounting to only a few thousand bytes, making
federated full-parameter tuning of billion-sized LLMs possible on devices.
Building on it, we develop a strategy enabling probability-differentiated seed
sampling, prioritizing perturbations with greater impact on model accuracy.
Experiments across six scenarios with various LLMs, datasets and data
partitions demonstrate that our approach outperforms existing federated LLM
fine-tuning methods in both communication efficiency and new task
generalization.
