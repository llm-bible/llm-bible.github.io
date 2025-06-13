---
layout: publication
title: 'Telelora: Teleporting Model-specific Alignment Across Llms'
authors: Xiao Lin, Manoj Acharya, Anirban Roy, Susmit Jha
conference: "Arxiv"
year: 2025
bibkey: lin2025teleporting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.20228"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Security']
---
Mitigating Trojans in Large Language Models (LLMs) is one of many tasks where
alignment data is LLM specific, as different LLMs have different Trojan
triggers and trigger behaviors to be removed. In this paper, we introduce
TeleLoRA (Teleporting Low-Rank Adaptation), a novel framework that synergizes
model-specific alignment data across multiple LLMs to enable zero-shot Trojan
mitigation on unseen LLMs without alignment data. TeleLoRA learns a unified
generator of LoRA adapter weights by leveraging local activation information
across multiple LLMs. This generator is designed to be permutation symmetric to
generalize across models with different architectures and sizes. We optimize
the model design for memory efficiency, making it feasible to learn with
large-scale LLMs with minimal computational resources. Experiments on LLM
Trojan mitigation benchmarks demonstrate that TeleLoRA effectively reduces
attack success rates while preserving the benign performance of the models.
