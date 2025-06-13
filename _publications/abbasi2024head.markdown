---
layout: publication
title: 'Normxlogit: The Head-on-top Never Lies'
authors: Sina Abbasi, Mohammad Reza Modarres, Mohammad Taher Pilehvar
conference: "Arxiv"
year: 2024
bibkey: abbasi2024head
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.16252"}
tags: ['Transformer', 'Pre-Training', 'Interpretability and Explainability', 'Model Architecture', 'Merging', 'Training Techniques', 'Pretraining Methods']
---
The Transformer architecture has emerged as the dominant choice for building
large language models (LLMs). However, with new LLMs emerging on a frequent
basis, it is important to consider the potential value of architecture-agnostic
approaches that can provide interpretability across a variety of architectures.
Despite recent successes in the interpretability of LLMs, many existing
approaches rely on complex methods that are often tied to a specific model
design and come with a significant computational cost. To address these
limitations, we propose a novel technique, called NormXLogit, for assessing the
significance of individual input tokens. This method operates based on the
input and output representations associated with each token. First, we
demonstrate that during the pre-training of LLMs, the norms of word embeddings
capture the importance of input tokens. Second, we reveal a significant
relationship between a token's importance and the extent to which its
representation can resemble the model's final prediction. Through extensive
analysis, we show that our approach consistently outperforms existing
gradient-based methods in terms of faithfulness. Additionally, our method
achieves better performance in layer-wise explanations compared to the most
prominent architecture-specific methods.
