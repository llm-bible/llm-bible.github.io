---
layout: publication
title: 'Lora-fa: Memory-efficient Low-rank Adaptation For Large Language Models Fine-tuning'
authors: Zhang Longteng, Zhang Lin, Shi Shaohuai, Chu Xiaowen, Li Bo
conference: "Arxiv"
year: 2023
bibkey: zhang2023lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.03303"}
tags: ['BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
The low-rank adaptation (LoRA) method can largely reduce the amount of
trainable parameters for fine-tuning large language models (LLMs), however, it
still requires expensive activation memory to update low-rank weights. Reducing
the number of LoRA layers or using activation recomputation could harm the
fine-tuning performance or increase the computational overhead. In this work,
we present LoRA-FA, a memory-efficient fine-tuning method that reduces the
activation memory without performance degradation and expensive recomputation.
LoRA-FA chooses to freeze the projection-down weight of \\(A\\) and update the
projection-up weight of \\(B\\) in each LoRA layer. It ensures the change of model
weight reside in a low-rank space during LLMs fine-tuning, while eliminating
the requirement to store full-rank input activations. We conduct extensive
experiments across multiple model types (RoBERTa, T5, LLaMA) and model scales.
Our results show that LoRA-FA can always achieve close fine-tuning accuracy
across different tasks compared to full parameter fine-tuning and LoRA.
Furthermore, LoRA-FA can reduce the overall memory cost by up to 1.4\\(\times\\)
compared to LoRA.
