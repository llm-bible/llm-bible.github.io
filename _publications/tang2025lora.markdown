---
layout: publication
title: 'Lora-null: Low-rank Adaptation Via Null Space For Large Language Models'
authors: Pengwei Tang, Yong Liu, Dongjie Zhang, Xing Wu, Debing Zhang
conference: "Arxiv"
year: 2025
bibkey: tang2025lora
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.02659"}
  - {name: "Code", url: "https://github.com/HungerPWAY/LoRA-Null"}
tags: ['Training Techniques', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Low-Rank Adaptation (LoRA) is the leading parameter-efficient fine-tuning
method for Large Language Models (LLMs). However, the fine-tuned LLMs encounter
the issue of catastrophic forgetting of the pre-trained world knowledge. To
address this issue, inspired by theoretical insights of null space, we propose
LoRA-Null, i.e., Low-Rank Adaptation via null space, which builds adapters
initialized from the null space of the pre-trained knowledge activation.
Concretely, we randomly collect a few data samples and capture their
activations after passing through the LLM layer. We perform Singular Value
Decomposition on the input activations to obtain their null space. We use the
projection of the pre-trained weights onto the null space as the initialization
for adapters. Experimental results demonstrate that this initialization
approach can effectively preserve the original pre-trained world knowledge of
the LLMs during fine-tuning. Additionally, if we freeze the values of the
down-projection matrices during fine-tuning, it achieves even better
preservation of the pre-trained world knowledge. LoRA-Null effectively
preserves pre-trained world knowledge while maintaining strong fine-tuning
performance, as validated by extensive experiments on LLaMA series (LLaMA2,
LLaMA3, LLaMA3.1, and LLaMA3.2) across Code, Math, and Instruction Following
tasks. We also provide a theoretical guarantee for the capacity of LoRA-Null to
retain pre-trained knowledge. Code is in
https://github.com/HungerPWAY/LoRA-Null.
