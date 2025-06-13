---
layout: publication
title: 'Reasoning Under 1 Billion: Memory-augmented Reinforcement Learning For Large Language Models'
authors: Hung Le, Dai Do, Dung Nguyen, Svetha Venkatesh
conference: "Arxiv"
year: 2025
bibkey: le2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.02273"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Recent advances in fine-tuning large language models (LLMs) with
reinforcement learning (RL) have shown promising improvements in complex
reasoning tasks, particularly when paired with chain-of-thought (CoT)
prompting. However, these successes have been largely demonstrated on
large-scale models with billions of parameters, where a strong pretraining
foundation ensures effective initial exploration. In contrast, RL remains
challenging for tiny LLMs with 1 billion parameters or fewer because they lack
the necessary pretraining strength to explore effectively, often leading to
suboptimal reasoning patterns. This work introduces a novel intrinsic
motivation approach that leverages episodic memory to address this challenge,
improving tiny LLMs in CoT reasoning tasks. Inspired by human memory-driven
learning, our method leverages successful reasoning patterns stored in memory
while allowing for controlled exploration to generate novel responses.
Intrinsic rewards are computed efficiently using a kNN-based episodic memory,
allowing the model to discover new reasoning strategies while quickly adapting
to effective past solutions. Experiments on fine-tuning GSM8K and AI-MO
datasets demonstrate that our approach significantly enhances smaller LLMs'
sample efficiency and generalization capability, making RL-based reasoning
improvements more accessible in low-resource settings.
