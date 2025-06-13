---
layout: publication
title: 'Linear Chain Transformation: Expanding Optimization Dynamics For Fine-tuning Large Language Models'
authors: Yulong Wang, Chang Zuo, Yin Xuan, Hong Li, Ni Wei
conference: "Arxiv"
year: 2024
bibkey: wang2024linear
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.00039'}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) has become essential for adapting
pretrained models to specific downstream tasks. In this paper, we propose
Linear Chain Transformation (LinChain), a novel approach that introduces a
sequence of linear transformations during fine-tuning to enrich optimization
dynamics. By incorporating multiple linear transformations into the parameter
update process, LinChain expands the effective rank of updates and enhances the
model's ability to learn complex task-specific representations. We demonstrate
that this method significantly improves the performance of LLM fine-tuning over
state-of-the-art methods by providing more flexible optimization paths during
training, while maintaining the inference efficiency of the resulting model.
Our experiments on various benchmark tasks show that LinChain leads to better
generalization, fewer learnable parameters, and improved task adaptation,
making it a compelling strategy for LLM fine-tuning.
