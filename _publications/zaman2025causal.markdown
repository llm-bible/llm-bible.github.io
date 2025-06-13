---
layout: publication
title: 'A Causal Lens For Evaluating Faithfulness Metrics'
authors: Kerem Zaman, Shashank Srivastava
conference: "Arxiv"
year: 2025
bibkey: zaman2025causal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18848'}
tags: ['Interpretability', 'Interpretability and Explainability', 'Tools']
---
Large Language Models (LLMs) offer natural language explanations as an
alternative to feature attribution methods for model interpretability. However,
despite their plausibility, they may not reflect the model's internal reasoning
faithfully, which is crucial for understanding the model's true decision-making
processes. Although several faithfulness metrics have been proposed, a unified
evaluation framework remains absent. To address this gap, we present Causal
Diagnosticity, a framework to evaluate faithfulness metrics for natural
language explanations. Our framework employs the concept of causal
diagnosticity, and uses model-editing methods to generate faithful-unfaithful
explanation pairs. Our benchmark includes four tasks: fact-checking, analogy,
object counting, and multi-hop reasoning. We evaluate a variety of faithfulness
metrics, including post-hoc explanation and chain-of-thought-based methods. We
find that all tested faithfulness metrics often fail to surpass a random
baseline. Our work underscores the need for improved metrics and more reliable
interpretability methods in LLMs.
