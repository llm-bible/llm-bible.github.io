---
layout: publication
title: 'Uncovering Uncertainty In Transformer Inference'
authors: Greyson Brothers, Willa Mannering, Amber Tien, John Winder
conference: "Arxiv"
year: 2024
bibkey: brothers2024uncovering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05768"}
tags: ['Transformer', 'Pretraining Methods', 'Model Architecture', 'Reinforcement Learning']
---
We explore the Iterative Inference Hypothesis (IIH) within the context of
transformer-based language models, aiming to understand how a model's latent
representations are progressively refined and whether observable differences
are present between correct and incorrect generations. Our findings provide
empirical support for the IIH, showing that the nth token embedding in the
residual stream follows a trajectory of decreasing loss. Additionally, we
observe that the rate at which residual embeddings converge to a stable output
representation reflects uncertainty in the token generation process. Finally,
we introduce a method utilizing cross-entropy to detect this uncertainty and
demonstrate its potential to distinguish between correct and incorrect token
generations on a dataset of idioms.
