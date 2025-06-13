---
layout: publication
title: 'Assessing Logical Reasoning Capabilities Of Encoder-only Transformer Models'
authors: Paulo Pirozelli, Marcos M. José, Paulo De Tarso P. Filho, Anarosa A. F. Brandão, Fabio G. Cozman
conference: "Arxiv"
year: 2023
bibkey: pirozelli2023assessing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.11720"}
tags: ['Pretraining Methods', 'Model Architecture', 'Transformer']
---
Logical reasoning is central to complex human activities, such as thinking,
debating, and planning; it is also a central component of many AI systems as
well. In this paper, we investigate the extent to which encoder-only
transformer language models (LMs) can reason according to logical rules. We ask
whether those LMs can deduce theorems in propositional calculus and first-order
logic; if their relative success in these problems reflects general logical
capabilities; and which layers contribute the most to the task. First, we show
for several encoder-only LMs that they can be trained, to a reasonable degree,
to determine logical validity on various datasets. Next, by cross-probing
fine-tuned models on these datasets, we show that LMs have difficulty in
transferring their putative logical reasoning ability, which suggests that they
may have learned dataset-specific features, instead of a general capability.
Finally, we conduct a layerwise probing experiment, which shows that the
hypothesis classification task is mostly solved through higher layers.
