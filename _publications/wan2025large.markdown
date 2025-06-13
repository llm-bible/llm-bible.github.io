---
layout: publication
title: 'Large Language Models As Computable Approximations To Solomonoff Induction'
authors: Jun Wan, Lingrui Mei
conference: "Arxiv"
year: 2025
bibkey: wan2025large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15784'}
tags: ['Large-Scale Training', 'Interpretability and Explainability', 'Few-Shot', 'RAG', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Training Techniques', 'Scaling Laws', 'Prompting', 'Reinforcement Learning', 'Pre-Training', 'In-Context Learning']
---
The rapid advancement of large language models (LLMs) calls for a rigorous theoretical framework to explain their empirical success. While significant progress has been made in understanding LLM behaviors, existing theoretical frameworks remain fragmented in explaining emergent phenomena through a unified mathematical lens. We establish the first formal connection between LLM architectures and Algorithmic Information Theory (AIT) by proving two fundamental results: (1) the training process computationally approximates Solomonoff prior through loss minimization interpreted as program length optimization, and (2) next-token prediction implements approximate Solomonoff induction. We leverage AIT to provide a unified theoretical explanation for in-context learning, few-shot learning, and scaling laws. Furthermore, our theoretical insights lead to a principled method for few-shot example selection that prioritizes samples where models exhibit lower predictive confidence. We demonstrate through experiments on diverse text classification benchmarks that this strategy yields significant performance improvements, particularly for smaller model architectures, when compared to selecting high-confidence examples. Our framework bridges the gap between theoretical foundations and practical LLM behaviors, providing both explanatory power and actionable insights for future model development.
