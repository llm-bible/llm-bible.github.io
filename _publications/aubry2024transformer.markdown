---
layout: publication
title: Transformer Alignment in Large Language Models
authors: Aubry Murdock, Meng Haoming, Sugolov Anton, Papyan Vardan
conference: "Arxiv"
year: 2024
bibkey: aubry2024transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.07810"}
tags: ['ARXIV', 'LLM', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Transformer']
---
Large Language Models (LLMs) have made significant strides in natural language processing and a precise understanding of the internal mechanisms driving their success is essential. We regard LLMs as transforming embeddings via a discrete coupled nonlinear dynamical system in high dimensions. This perspective motivates tracing the trajectories of individual tokens as they pass through transformer blocks and linearizing the system along these trajectories through their Jacobian matrices. In our analysis of 38 openly available LLMs we uncover the alignment of top left and right singular vectors of Residual Jacobians as well as the emergence of linearity and layer-wise exponential growth. Notably we discover that increased alignment with model performance. Metrics evaluated post-training show significant improvement in comparison to measurements made with randomly initialized weights highlighting the significant effects of training in transformers. These findings reveal a remarkable level of regularity that has previously been overlooked reinforcing the dynamical interpretation and paving the way for deeper understanding and optimization of LLM architectures.
