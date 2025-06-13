---
layout: publication
title: 'Autohete: An Automatic And Efficient Heterogeneous Training System For Llms'
authors: Zihao Zeng, Chubo Liu, Xin He, Juan Hu, Yong Jiang, Fei Huang, Kenli Li, Wei Yang Bryan Lim
conference: "Arxiv"
year: 2025
bibkey: zeng2025automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01890"}
tags: ['Transformer', 'Applications', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Transformer-based large language models (LLMs) have demonstrated exceptional
capabilities in sequence modeling and text generation, with improvements
scaling proportionally with model size. However, the limitations of GPU memory
have restricted LLM training accessibility for many researchers. Existing
heterogeneous training methods significantly expand the scale of trainable
models but introduce substantial communication overheads and CPU workloads. In
this work, we propose AutoHete, an automatic and efficient heterogeneous
training system compatible with both single-GPU and multi-GPU environments.
AutoHete dynamically adjusts activation checkpointing, parameter offloading,
and optimizer offloading based on the specific hardware configuration and LLM
training needs. Additionally, we design a priority-based scheduling mechanism
that maximizes the overlap between operations across training iterations,
enhancing throughput. Compared to state-of-the-art heterogeneous training
systems, AutoHete delivers a 1.32x~1.91x throughput improvement across various
model sizes and training configurations.
