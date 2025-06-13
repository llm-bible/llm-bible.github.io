---
layout: publication
title: 'New Desiderata For Direct Preference Optimization'
authors: Xiangkun Hu, Tong He, David Wipf
conference: "Arxiv"
year: 2024
bibkey: hu2024new
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.09072'}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models in the past have typically relied on some form of
reinforcement learning with human feedback (RLHF) to better align model
responses with human preferences. However, because of oft-observed
instabilities when implementing these RLHF pipelines, various
reparameterization techniques have recently been introduced to sidestep the
need for separately learning an RL reward model. Instead, directly fine-tuning
for human preferences is achieved via the minimization of a single closed-form
training objective, a process originally referred to as direct preference
optimization (DPO) and followed by several notable descendants. Although
effective in certain real-world settings, we introduce new evaluation criteria
that serve to highlight unresolved shortcomings in the ability of existing DPO
methods to interpolate between a pre-trained reference model and empirical
measures of human preferences, as well as unavoidable trade-offs in how low-
and high-quality responses are regularized and constraints are handled. Our
insights then motivate an alternative DPO-like loss that provably mitigates
these limitations. Empirical results serve to corroborate notable aspects of
our analyses.
