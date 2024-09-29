---
layout: publication
title: Meteora\: Multiple-tasks Embedded Lora For Large Language Models
authors: Xu Jingwei, Lai Junyu, Huang Yunpeng
conference: "Arxiv"
year: 2024
bibkey: xu2024multiple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13053"}
tags: ['Applications', 'Fine Tuning', 'Merging', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
The pretrain+fine-tune paradigm is foundational in deploying large language models (LLMs) across a diverse range of downstream applications. Among these Low-Rank Adaptation (LoRA) stands out for its parameter-efficient fine-tuning (PEFT) producing numerous off-the-shelf task-specific LoRA adapters. However this approach requires explicit task intention selection posing challenges for automatic task sensing and switching during inference with multiple existing LoRA adapters embedded in a single LLM. In this work we introduce MeteoRA (Multiple-Tasks embedded LoRA) a scalable multi-knowledge LoRA fusion framework designed for LLMs. MeteoRA integrates various LoRA adapters in a Mixture-of-Experts (MoE) style into the base LLM enabling the model to automatically select the most pertinent adapter based on the task input. This advancement significantly enhances the LLMs capability to handle composite tasks that require different adapters to solve various components of the problem. Our evaluations featuring the LlaMA2-13B and LlaMA3-8B base models equipped with off-the-shelf 28 LoRA adapters through MeteoRA demonstrate equivalent performance with the individual adapters. Furthermore both base models equipped with MeteoRA achieve superior performance in sequentially solving composite tasks with ten problems in only a single inference process highlighting the ability of timely intention switching in MeteoRA embedded LLMs.
