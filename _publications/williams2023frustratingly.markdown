---
layout: publication
title: Frustratingly Simple Memory Efficiency For Pre45;trained Language Models Via Dynamic Embedding Pruning
authors: Williams Miles, Aletras Nikolaos
conference: "Arxiv"
year: 2023
bibkey: williams2023frustratingly
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.08708"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'RAG', 'Transformer']
---
The extensive memory footprint of pre45;trained language models (PLMs) can hinder deployment in memory45;constrained settings such as cloud environments or on45;device. PLMs use embedding matrices to represent extensive vocabularies forming a large proportion of the model parameters. While previous work towards parameter45;efficient PLM development has considered pruning parameters within the transformer layers pruning the embedding matrix as part of fine45;tuning or inference has yet to be explored. We first demonstrate that a significant proportion of the vocabulary remains unused in these scenarios. We then propose a simple yet effective approach that leverages this finding to minimize the memory footprint of the embedding matrix. We show that this approach provides substantial reductions in memory usage across a wide range of models and tasks. Notably our approach maintains equivalent downstream task performance while allowing a more efficient use of compute resources.
