---
layout: publication
title: 'Stable Language Model Pre-training By Reducing Embedding Variability'
authors: Woojin Chung, Jiwoo Hong, Na Min An, James Thorne, Se-young Yun
conference: "Arxiv"
year: 2024
bibkey: chung2024stable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.07787"}
tags: ['Pre-Training', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism']
---
Stable pre-training is essential for achieving better-performing language
models. However, tracking pre-training stability by calculating gradient
variance at every step is impractical due to the significant computational
costs. We explore Token Embedding Variability (TEV) as a simple and efficient
proxy for assessing pre-training stability in language models with pre-layer
normalization, given that shallower layers are more prone to gradient explosion
(section 2.2). Moreover, we propose Multi-head Low-Rank Attention (MLRA) as an
architecture to alleviate such instability by limiting the exponential growth
of output embedding variance, thereby preventing the gradient explosion
(section 3.2). Empirical results on GPT-2 with MLRA demonstrate increased
stability and lower perplexity, particularly in deeper models.
