---
layout: publication
title: 'Understanding LLM Embeddings For Regression'
authors: Eric Tang, Bangding Yang, Xingyou Song
conference: "Arxiv"
year: 2024
bibkey: tang2024understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.14708'}
tags: ['Uncategorized']
---
With the rise of large language models (LLMs) for flexibly processing
information as strings, a natural application is regression, specifically by
preprocessing string representations into LLM embeddings as downstream features
for metric prediction. In this paper, we provide one of the first comprehensive
investigations into embedding-based regression and demonstrate that LLM
embeddings as features can be better for high-dimensional regression tasks than
using traditional feature engineering. This regression performance can be
explained in part due to LLM embeddings over numeric data inherently preserving
Lipschitz continuity over the feature space. Furthermore, we quantify the
contribution of different model effects, most notably model size and language
understanding, which we find surprisingly do not always improve regression
performance.
