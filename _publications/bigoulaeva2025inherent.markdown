---
layout: publication
title: 'The Inherent Limits Of Pretrained Llms: The Unexpected Convergence Of Instruction Tuning And In-context Learning Capabilities'
authors: Irina Bigoulaeva, Harish Tayyar Madabushi, Iryna Gurevych
conference: "Arxiv"
year: 2025
bibkey: bigoulaeva2025inherent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.08716"}
tags: ['Fine-Tuning', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs), trained on extensive web-scale corpora, have
demonstrated remarkable abilities across diverse tasks, especially as they are
scaled up. Nevertheless, even state-of-the-art models struggle in certain
cases, sometimes failing at problems solvable by young children, indicating
that traditional notions of task complexity are insufficient for explaining LLM
capabilities. However, exploring LLM capabilities is complicated by the fact
that most widely-used models are also "instruction-tuned" to respond
appropriately to prompts. With the goal of disentangling the factors
influencing LLM performance, we investigate whether instruction-tuned models
possess fundamentally different capabilities from base models that are prompted
using in-context examples. Through extensive experiments across various model
families, scales and task types, which included instruction tuning 90 different
LLMs, we demonstrate that the performance of instruction-tuned models is
significantly correlated with the in-context performance of their base
counterparts. By clarifying what instruction-tuning contributes, we extend
prior research into in-context learning, which suggests that base models use
priors from pretraining data to solve tasks. Specifically, we extend this
understanding to instruction-tuned models, suggesting that their pretraining
data similarly sets a limiting boundary on the tasks they can solve, with the
added influence of the instruction-tuning dataset.
