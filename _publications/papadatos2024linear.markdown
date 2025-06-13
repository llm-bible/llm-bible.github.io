---
layout: publication
title: 'Linear Probe Penalties Reduce LLM Sycophancy'
authors: Henry Papadatos, Rachel Freedman
conference: "Arxiv"
year: 2024
bibkey: papadatos2024linear
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.00967"}
tags: ['Fine-Tuning', 'Agentic', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) are often sycophantic, prioritizing agreement
with their users over accurate or objective statements. This problematic
behavior becomes more pronounced during reinforcement learning from human
feedback (RLHF), an LLM fine-tuning stage intended to align model outputs with
human values. Instead of increasing accuracy and reliability, the reward model
learned from RLHF often rewards sycophancy. We develop a linear probing method
to identify and penalize markers of sycophancy within the reward model,
producing rewards that discourage sycophantic behavior. Our experiments show
that constructing and optimizing against this surrogate reward function reduces
sycophantic behavior in multiple open-source LLMs. Our results suggest a
generalizable methodology for reducing unwanted LLM behaviors that are not
sufficiently disincentivized by RLHF fine-tuning.
