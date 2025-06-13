---
layout: publication
title: 'Tending Towards Stability: Convergence Challenges In Small Language Models'
authors: Richard Diehl Martinez, Pietro Lesci, Paula Buttery
conference: "Arxiv"
year: 2024
bibkey: martinez2024tending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.11451"}
tags: ['Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Increasing the number of parameters in language models is a common strategy
to enhance their performance. However, smaller language models remain valuable
due to their lower operational costs. Despite their advantages, smaller models
frequently underperform compared to their larger counterparts, even when
provided with equivalent data and computational resources. Specifically, their
performance tends to degrade in the late pretraining phase. This is anecdotally
attributed to their reduced representational capacity. Yet, the exact causes of
this performance degradation remain unclear. We use the Pythia model suite to
analyse the training dynamics that underlie this phenomenon. Across different
model sizes, we investigate the convergence of the Attention and MLP
activations to their final state and examine how the effective rank of their
parameters influences this process. We find that nearly all layers in larger
models stabilise early in training - within the first 20% - whereas layers in
smaller models exhibit slower and less stable convergence, especially when
their parameters have lower effective rank. By linking the convergence of
layers' activations to their parameters' effective rank, our analyses can guide
future work to address inefficiencies in the learning dynamics of small models.
