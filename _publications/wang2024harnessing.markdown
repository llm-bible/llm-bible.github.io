---
layout: publication
title: 'Milora: Harnessing Minor Singular Components For Parameter-efficient LLM Finetuning'
authors: Hanqing Wang, Yixia Li, Shuo Wang, Guanhua Chen, Yun Chen
conference: "Arxiv"
year: 2024
bibkey: wang2024harnessing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.09044'}
tags: ['Fine-Tuning']
---
Efficient finetuning of large language models (LLMs) aims to adapt the LLMs
with reduced computational and memory cost. Previous LoRA-based approaches
initialize the low-rank matrices with Gaussian distribution and zero values
while keeping the original weight matrices frozen. However, the trainable model
parameters optimized in an unguided subspace might interfere with the
well-learned subspace of the pretrained weight matrices. In this paper, we
propose MiLoRA, a simple yet effective LLM finetuning approach that only
updates the minor singular components of the weight matrix while keeping the
principal singular components frozen. It is observed that the minor matrix
corresponds to the noisy or long-tail information, while the principal matrix
contains important knowledge. The MiLoRA initializes the low-rank matrices
within a subspace that is orthogonal to the principal matrix, thus the
pretrained knowledge is expected to be well preserved. During finetuning,
MiLoRA makes the most use of the less-optimized subspace for learning the
labeled dataset. Extensive experiments on commonsense reasoning, math
reasoning, instruction following and visual instruction following benchmarks
present the superior performance of our method.
