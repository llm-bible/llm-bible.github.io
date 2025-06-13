---
layout: publication
title: 'Simpletron: Simple Transformer With O(N) Complexity'
authors: Uladzislau Yorsh, Alexander Kovalenko, Vojtěch Vančura, Daniel Vašata, Pavel Kordík, Tomáš Mikolov
conference: "Arxiv"
year: 2021
bibkey: yorsh2021simple
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2111.15588'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Tools', 'Pretraining Methods']
---
In this paper, we propose that the dot product pairwise matching attention
layer, which is widely used in Transformer-based models, is redundant for the
model performance. Attention, in its original formulation, has to be seen
rather as a human-level tool to explore and/or visualize relevancy scores in
sequential data. However, the way how it is constructed leads to significant
computational complexity. Instead, we present SimpleTRON: Simple Transformer
with O(N) Complexity, a simple and fast alternative without any approximation
that, unlike other approximation models, does not have any architecture-related
overhead and therefore can be seen as a purely linear Transformer-like model.
This architecture, to the best of our knowledge, outperforms existing
sub-quadratic attention approximation models on several tasks from the
Long-Range Arena benchmark. Moreover, we show, that SimpleTRON can benefit from
weight transfer from pretrained large language models, as its parameters can be
fully transferable.
