---
layout: publication
title: 'LESA: Learnable LLM Layer Scaling-up'
authors: Yifei Yang, Zouying Cao, Xinbei Ma, Yao Yao, Libo Qin, Zhi Chen, Hai Zhao
conference: "Arxiv"
year: 2025
bibkey: yang2025learnable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.13794'}
tags: ['RAG', 'Pre-Training', 'Training Techniques', 'Scaling Laws']
---
Training Large Language Models (LLMs) from scratch requires immense
computational resources, making it prohibitively expensive. Model scaling-up
offers a promising solution by leveraging the parameters of smaller models to
create larger ones. However, existing depth scaling-up methods rely on
empirical heuristic rules for layer duplication, which result in poorer
initialization and slower convergence during continual pre-training. We propose
\textbf\{LESA\}, a novel learnable method for depth scaling-up. By concatenating
parameters from each layer and applying Singular Value Decomposition, we
uncover latent patterns between layers, suggesting that inter-layer parameters
can be learned. LESA uses a neural network to predict the parameters inserted
between adjacent layers, enabling better initialization and faster training.
Experiments show that LESA outperforms existing baselines, achieving superior
performance with less than half the computational cost during continual
pre-training. Extensive analyses demonstrate its effectiveness across different
model sizes and tasks.
