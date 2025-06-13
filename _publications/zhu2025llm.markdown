---
layout: publication
title: 'LLM As GNN: Graph Vocabulary Learning For Text-attributed Graph Foundation Models'
authors: Xi Zhu, Haochen Xue, Ziwei Zhao, Wujiang Xu, Jingyuan Huang, Minghao Guo, Qifan Wang, Kaixiong Zhou, Yongfeng Zhang
conference: "Arxiv"
year: 2025
bibkey: zhu2025llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.03313'}
  - {name: "Code", url: 'https://github.com/agiresearch/PromptGFM'}
tags: ['Has Code', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Text-Attributed Graphs (TAGs), where each node is associated with text
descriptions, are ubiquitous in real-world scenarios. They typically exhibit
distinctive structure and domain-specific knowledge, motivating the development
of a Graph Foundation Model (GFM) that generalizes across diverse graphs and
tasks. Despite large efforts to integrate Large Language Models (LLMs) and
Graph Neural Networks (GNNs) for TAGs, existing approaches suffer from
decoupled architectures with two-stage alignment, limiting their synergistic
potential. Even worse, existing methods assign out-of-vocabulary (OOV) tokens
to graph nodes, leading to graph-specific semantics, token explosion, and
incompatibility with task-oriented prompt templates, which hinders cross-graph
and cross-task transferability. To address these challenges, we propose
PromptGFM, a versatile GFM for TAGs grounded in graph vocabulary learning.
PromptGFM comprises two key components: (1) Graph Understanding Module, which
explicitly prompts LLMs to replicate the finest GNN workflow within the text
space, facilitating seamless GNN-LLM integration and elegant graph-text
alignment; (2) Graph Inference Module, which establishes a language-based graph
vocabulary ensuring expressiveness, transferability, and scalability, enabling
readable instructions for LLM fine-tuning. Extensive experiments demonstrate
our superiority and transferability across diverse graphs and tasks. The code
is available at this: https://github.com/agiresearch/PromptGFM.
