---
layout: publication
title: 'Layer By Layer: Uncovering Hidden Representations In Language Models'
authors: Oscar Skean, Md Rifat Arefin, Dan Zhao, Niket Patel, Jalal Naghiyev, Yann Lecun, Ravid Shwartz-ziv
conference: "Arxiv"
year: 2025
bibkey: skean2025layer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.02013'}
tags: ['Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods']
---
From extracting features to generating text, the outputs of large language
models (LLMs) typically rely on their final layers, following the conventional
wisdom that earlier layers capture only low-level cues. However, our analysis
shows that intermediate layers can encode even richer representations, often
improving performance on a wide range of downstream tasks. To explain and
quantify these hidden-layer properties, we propose a unified framework of
representation quality metrics based on information theory, geometry, and
invariance to input perturbations. Our framework highlights how each model
layer balances information compression and signal preservation, revealing why
mid-depth embeddings can exceed the last layer's performance. Through extensive
experiments on 32 text-embedding tasks and comparisons across model
architectures (transformers, state-space models) and domains (language,
vision), we demonstrate that intermediate layers consistently provide stronger
features. These findings challenge the standard focus on final-layer embeddings
and open new directions for model analysis and optimization, including
strategic use of mid-layer representations for more robust and accurate AI
systems.
