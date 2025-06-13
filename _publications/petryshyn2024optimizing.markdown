---
layout: publication
title: 'Optimizing Large Language Models For Openapi Code Completion'
authors: Bohdan Petryshyn, Mantas Lukoševičius
conference: "Arxiv"
year: 2024
bibkey: petryshyn2024optimizing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.15729'}
tags: ['RAG', 'Efficiency and Optimization', 'Applications', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advancements in Large Language Models (LLMs) and their utilization in
code generation tasks have significantly reshaped the field of software
development. Despite the remarkable efficacy of code completion solutions in
mainstream programming languages, their performance lags when applied to less
ubiquitous formats such as OpenAPI definitions. This study evaluates the
OpenAPI completion performance of GitHub Copilot, a prevalent commercial code
completion tool, and proposes a set of task-specific optimizations leveraging
Meta's open-source model Code Llama. A semantics-aware OpenAPI completion
benchmark proposed in this research is used to perform a series of experiments
through which the impact of various prompt-engineering and fine-tuning
techniques on the Code Llama model's performance is analyzed. The fine-tuned
Code Llama model reaches a peak correctness improvement of 55.2% over GitHub
Copilot despite utilizing 25 times fewer parameters than the commercial
solution's underlying Codex model. Additionally, this research proposes an
enhancement to a widely used code infilling training technique, addressing the
issue of underperformance when the model is prompted with context sizes smaller
than those used during training. The dataset, the benchmark, and the model
fine-tuning code are made publicly available.
