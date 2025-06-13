---
layout: publication
title: 'Scalable Multi-domain Adaptation Of Language Models Using Modular Experts'
authors: Peter Schafhalter, Shun Liao, Yanqi Zhou, Chih-kuan Yeh, Arun Kandoor, James Laudon
conference: "Arxiv"
year: 2024
bibkey: schafhalter2024scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10181"}
tags: ['Fine-Tuning', 'Transformer', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Large-Scale Training', 'Training Techniques', 'Pretraining Methods']
---
Domain-specific adaptation is critical to maximizing the performance of
pre-trained language models (PLMs) on one or multiple targeted tasks,
especially under resource-constrained use cases, such as edge devices. However,
existing methods often struggle to balance domain-specific performance,
retention of general knowledge, and efficiency for training and inference. To
address these challenges, we propose Modular Domain Experts (MoDE). MoDE is a
mixture-of-experts architecture that augments a general PLMs with modular,
domain-specialized experts. These experts are trained independently and
composed together via a lightweight training process. In contrast to standard
low-rank adaptation methods, each MoDE expert consists of several transformer
layers which scale better with more training examples and larger parameter
counts. Our evaluation demonstrates that MoDE achieves comparable target
performances to full parameter fine-tuning while achieving 1.65% better
retention performance. Moreover, MoDE's architecture enables flexible sharding
configurations and improves training speeds by up to 38% over state-of-the-art
distributed training configurations.
