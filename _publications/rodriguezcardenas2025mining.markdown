---
layout: publication
title: 'Snipgen: A Mining Repository Framework For Evaluating Llms For Code'
authors: Daniel Rodriguez-cardenas, Alejandro Velasco, Denys Poshyvanyk
conference: "Arxiv"
year: 2025
bibkey: rodriguezcardenas2025mining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07046"}
tags: ['Fine-Tuning', 'Transformer', 'Tools', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Language Models (LLMs), such as transformer-based neural networks trained on
billions of parameters, have become increasingly prevalent in software
engineering (SE). These models, trained on extensive datasets that include code
repositories, exhibit remarkable capabilities for SE tasks. However, evaluating
their effectiveness poses significant challenges, primarily due to the
potential overlap between the datasets used for training and those employed for
evaluation. To address this issue, we introduce SnipGen, a comprehensive
repository mining framework designed to leverage prompt engineering across
various downstream tasks for code generation. SnipGen aims to mitigate data
contamination by generating robust testbeds and crafting tailored data points
to assist researchers and practitioners in evaluating LLMs for code-related
tasks. In our exploratory study, SnipGen mined approximately 227K data points
from 338K recent code changes in GitHub commits, focusing on method-level
granularity. SnipGen features a collection of prompt templates that can be
combined to create a Chain-of-Thought-like sequence of prompts, enabling a
nuanced assessment of LLMs' code generation quality. By providing the mining
tool, the methodology, and the dataset, SnipGen empowers researchers and
practitioners to rigorously evaluate and interpret LLMs' performance in
software engineering contexts.
