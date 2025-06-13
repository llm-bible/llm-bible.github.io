---
layout: publication
title: 'Taipan: Efficient And Expressive State Space Language Models With Selective Attention'
authors: Chien Van Nguyen, Huy Huu Nguyen, Thang M. Pham, Ruiyi Zhang, Hanieh Deilamsalehy, Puneet Mathur, Ryan A. Rossi, Trung Bui, Viet Dac Lai, Franck Dernoncourt, Thien Huu Nguyen
conference: "Arxiv"
year: 2024
bibkey: vannguyen2024efficient
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18572"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Efficient long-context language modeling remains a significant challenge in
Natural Language Processing (NLP). While Transformers dominate language tasks,
they struggle with long sequences due to quadratic computational complexity in
training and linearly scaling memory costs during inference. Recent State Space
Models (SSMs) such as Mamba offer alternatives with constant memory usage, but
they underperform in tasks requiring extensive in-context retrieval. We
introduce Taipan, a novel hybrid architecture that combines Mamba-2 with
Selective Attention Layers (SALs). These SALs identify tokens requiring
long-range interactions, remove less important features, and then augment their
representations using the attention module. This approach balances Mamba's
efficiency with Transformer-like performance in memory-intensive tasks. By
constraining the attention budget, Taipan extends accurate predictions to
context lengths of up to 1 million tokens while preserving computational
efficiency. Our experiments demonstrate Taipan's superior performance across
various scales and tasks, offering a promising solution for efficient
long-context language modeling.
