---
layout: publication
title: How Truncating Weights Improves Reasoning In Language Models
authors: Chen Lei, Bruna Joan, Bietti Alberto
conference: "Arxiv"
year: 2024
bibkey: chen2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03068"}
tags: ['Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
In addition to the ability to generate fluent text in various languages large language models have been successful at tasks that involve basic forms of logical reasoning over their context. Recent work found that selectively removing certain components from weight matrices in pre-trained models can improve such reasoning capabilities. We investigate this phenomenon further by carefully studying how certain global associations tend to be stored in specific weight components or Transformer blocks in particular feed-forward layers. Such associations may hurt predictions in reasoning tasks and removing the corresponding components may then improve performance. We analyze how this arises during training both empirically and theoretically on a two-layer Transformer trained on a basic reasoning task with noise a toy associative memory model and on the Pythia family of pre-trained models tested on simple reasoning tasks.
