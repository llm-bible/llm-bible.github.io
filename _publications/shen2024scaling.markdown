---
layout: publication
title: 'Scaling Laws For Linear Complexity Language Models'
authors: Shen Xuyang, Li Dong, Leng Ruitao, Qin Zhen, Sun Weigao, Zhong Yiran
conference: "Arxiv"
year: 2024
bibkey: shen2024scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16690"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'Scaling Laws', 'Transformer']
---
The interest in linear complexity models for large language models is on the
rise, although their scaling capacity remains uncertain. In this study, we
present the scaling laws for linear complexity language models to establish a
foundation for their scalability. Specifically, we examine the scaling
behaviors of three efficient linear architectures. These include TNL, a linear
attention model with data-independent decay; HGRN2, a linear RNN with
data-dependent decay; and cosFormer2, a linear attention model without decay.
We also include LLaMA as a baseline architecture for softmax attention for
comparison. These models were trained with six variants, ranging from 70M to 7B
parameters on a 300B-token corpus, and evaluated with a total of 1,376
intermediate checkpoints on various downstream tasks. These tasks include
validation loss, commonsense reasoning, and information retrieval and
generation. The study reveals that existing linear complexity language models
exhibit similar scaling capabilities as conventional transformer-based models
while also demonstrating superior linguistic proficiency and knowledge
retention.
