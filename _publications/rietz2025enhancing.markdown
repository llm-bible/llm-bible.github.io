---
layout: publication
title: 'Enhancing Pre-trained Decision Transformers With Prompt-tuning Bandits'
authors: Finn Rietz, Oleg Smirnov, Sara Karimi, Lele Cao
conference: "Arxiv"
year: 2025
bibkey: rietz2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.04979"}
tags: ['Transformer', 'Pre-Training', 'Agentic', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Harnessing large offline datasets is vital for training foundation models
that can generalize across diverse tasks. Offline Reinforcement Learning (RL)
offers a powerful framework for these scenarios, enabling the derivation of
optimal policies even from suboptimal data. The Prompting Decision Transformer
(PDT) is an offline RL multi-task model that distinguishes tasks through
stochastic trajectory prompts, which are task-specific tokens maintained in
context during rollouts. However, PDT samples these tokens uniformly at random
from per-task demonstration datasets, failing to account for differences in
token informativeness and potentially leading to performance degradation. To
address this limitation, we introduce a scalable bandit-based prompt-tuning
method that dynamically learns to construct high-performance trajectory
prompts. Our approach significantly enhances downstream task performance
without modifying the pre-trained Transformer backbone. Empirical results on
benchmark tasks and a newly designed multi-task environment demonstrate the
effectiveness of our method, creating a seamless bridge between general
multi-task offline pre-training and task-specific online adaptation.
