---
layout: publication
title: 'Scaling Laws For Upcycling Mixture-of-experts Language Models'
authors: Seng Pei Liew, Takuya Kato, Sho Takase
conference: "Arxiv"
year: 2025
bibkey: liew2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.03009"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Scaling Laws', 'Reinforcement Learning', 'Pretraining Methods', 'Large-Scale Training', 'Pre-Training']
---
Pretraining large language models (LLMs) is resource-intensive, often
requiring months of training time even with high-end GPU clusters. There are
two approaches of mitigating such computational demands: reusing smaller models
to train larger ones (upcycling), and training computationally efficient models
like mixture-of-experts (MoE). In this paper, we study the upcycling of LLMs to
MoE models, of which the scaling behavior remains underexplored. Through
extensive experiments, we identify empirical scaling laws that describe how
performance depends on dataset size and model configuration. Particularly, we
show that, while scaling these factors improves performance, there is a novel
interaction term between the dense and upcycled training dataset that limits
the efficiency of upcycling at large computational budgets. Based on these
findings, we provide guidance to scale upcycling, and establish conditions
under which upcycling outperforms from-scratch trainings within budget
constraints.
