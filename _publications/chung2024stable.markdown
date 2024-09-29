---
layout: publication
title: Stable Language Model Pre45;training By Reducing Embedding Variability
authors: Chung Woojin, Hong Jiwoo, An Na Min, Thorne James, Yun Se-young
conference: "Arxiv"
year: 2024
bibkey: chung2024stable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.07787"}
tags: ['Attention Mechanism', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques']
---
Stable pre45;training is essential for achieving better45;performing language models. However tracking pre45;training stability by calculating gradient variance at every step is impractical due to the significant computational costs. We explore Token Embedding Variability (TEV) as a simple and efficient proxy for assessing pre45;training stability in language models with pre45;layer normalization given that shallower layers are more prone to gradient explosion (section 2.2). Moreover we propose Multi45;head Low45;Rank Attention (MLRA) as an architecture to alleviate such instability by limiting the exponential growth of output embedding variance thereby preventing the gradient explosion (section 3.2). Empirical results on GPT45;2 with MLRA demonstrate increased stability and lower perplexity particularly in deeper models.
