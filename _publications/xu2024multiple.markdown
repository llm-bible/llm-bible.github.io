---
layout: publication
title: 'Meteora: Multiple-tasks Embedded Lora For Large Language Models'
authors: Jingwei Xu, Junyu Lai, Yunpeng Huang
conference: "Arxiv"
year: 2024
bibkey: xu2024multiple
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.13053'}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Applications', 'Tools', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
The pretrain+fine-tune paradigm is foundational for deploying large language
models (LLMs) across various downstream applications. Within this framework,
Low-Rank Adaptation (LoRA) stands out for its parameter-efficient fine-tuning
(PEFT), producing numerous reusable task-specific LoRA adapters. However, this
approach requires explicit task intention selection, posing challenges for
autonomous task sensing and switching during inference with multiple existing
LoRA adapters embedded in a single LLM. In this work, we introduce MeteoRA
(Multiple-tasks embedded LoRA), a scalable and efficient framework that reuses
multiple task-specific LoRA adapters into the base LLM via a full-mode
Mixture-of-Experts (MoE) architecture. This framework also includes novel MoE
forward acceleration strategies to address the efficiency challenges of
traditional MoE implementations. Our evaluation, using the LlaMA2-13B and
LlaMA3-8B base models equipped with 28 existing LoRA adapters through MeteoRA,
demonstrates equivalent performance with the traditional PEFT method. Moreover,
the LLM equipped with MeteoRA achieves superior performance in handling
composite tasks, effectively solving ten sequential problems in a single
inference pass, thereby demonstrating the framework's enhanced capability for
timely adapter switching.
