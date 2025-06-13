---
layout: publication
title: 'Communication-efficient Language Model Training Scales Reliably And Robustly: Scaling Laws For Diloco'
authors: Zachary Charles, Gabriel Teston, Lucio Dery, Keith Rush, Nova Fallen, Zachary Garrett, Arthur Szlam, Arthur Douillard
conference: "Arxiv"
year: 2025
bibkey: charles2025communication
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.09799"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Model Architecture', 'Large-Scale Training', 'Training Techniques', 'Scaling Laws']
---
As we scale to more massive machine learning models, the frequent
synchronization demands inherent in data-parallel approaches create significant
slowdowns, posing a critical challenge to further scaling. Recent work develops
an approach (DiLoCo) that relaxes synchronization demands without compromising
model quality. However, these works do not carefully analyze how DiLoCo's
behavior changes with model size. In this work, we study the scaling law
behavior of DiLoCo when training LLMs under a fixed compute budget. We focus on
how algorithmic factors, including number of model replicas, hyperparameters,
and token budget affect training in ways that can be accurately predicted via
scaling laws. We find that DiLoCo scales both predictably and robustly with
model size. When well-tuned, DiLoCo scales better than data-parallel training
with model size, and can outperform data-parallel training even at small model
sizes. Our results showcase a more general set of benefits of DiLoCo than
previously documented, including increased optimal batch sizes, improved
downstream generalization with scale, and improved evaluation loss for a fixed
token budget.
