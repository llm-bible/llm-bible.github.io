---
layout: publication
title: 'Sparks Of Tabular Reasoning Via Text2sql Reinforcement Learning'
authors: Josefa Lia Stoisser, Marc Boubnovski Martell, Julien Fauqueur
conference: "Arxiv"
year: 2025
bibkey: stoisser2025sparks
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00016"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning']
---
This work reframes the Text-to-SQL task as a pathway for teaching large
language models (LLMs) to reason over and manipulate tabular data--moving
beyond the traditional focus on query generation. We propose a two-stage
framework that leverages SQL supervision to develop transferable table
reasoning capabilities. First, we synthesize detailed chain-of-thought (CoT)
traces from real-world SQL queries, providing step-by-step, clause-level
supervision that teaches the model how to traverse, filter, and aggregate table
fields. Second, we introduce a Group Relative Policy Optimization (GRPO)
reinforcement learning objective that connects SQL execution accuracy to
generalizable reasoning by encouraging steps that extend beyond task-specific
syntax and transfer across datasets. Empirically, our approach improves
performance on standard Text-to-SQL benchmarks and achieves substantial gains
on reasoning-intensive datasets such as BIRD and CRT-QA, demonstrating enhanced
generalization and interpretability. Specifically, the distilled-quantized
LLaMA model achieved a relative 33.9% increase in accuracy when trained on
Text-to-SQL tasks, while Qwen achieved a relative 14.5% increase. These
results suggest that SQL can serve not only as a target formalism but also as
an effective scaffold for learning robust, transferable reasoning over
structured data.
