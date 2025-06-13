---
layout: publication
title: 'Training Language Models To Reason Efficiently'
authors: Daman Arora, Andrea Zanette
conference: "Arxiv"
year: 2025
bibkey: arora2025training
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.04463'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning']
---
Scaling model size and training data has led to great advances in the performance of Large Language Models (LLMs). However, the diminishing returns of this approach necessitate alternative methods to improve model capabilities, particularly in tasks requiring advanced reasoning. Large reasoning models, which leverage long chain-of-thoughts, bring unprecedented breakthroughs in problem-solving capabilities but at a substantial deployment cost associated to longer generations. Reducing inference costs is crucial for the economic feasibility, user experience, and environmental sustainability of these models.
  In this work, we propose to train large reasoning models to reason efficiently. More precisely, we use reinforcement learning (RL) to train reasoning models to dynamically allocate inference-time compute based on task complexity. Our method incentivizes models to minimize unnecessary computational overhead while maintaining accuracy, thereby achieving substantial efficiency gains. It enables the derivation of a family of reasoning models with varying efficiency levels, controlled via a single hyperparameter. Experiments on two open-weight large reasoning models demonstrate significant reductions in inference cost while preserving most of the accuracy.
