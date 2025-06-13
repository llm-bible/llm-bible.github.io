---
layout: publication
title: 'Memory-efficient Transformers Via Top-\(k\) Attention'
authors: Ankit Gupta, Guy Dar, Shaya Goodman, David Ciprut, Jonathan Berant
conference: "Arxiv"
year: 2021
bibkey: gupta2021memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.06899"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Following the success of dot-product attention in Transformers, numerous
approximations have been recently proposed to address its quadratic complexity
with respect to the input length. While these variants are memory and compute
efficient, it is not possible to directly use them with popular pre-trained
language models trained using vanilla attention, without an expensive
corrective pre-training stage. In this work, we propose a simple yet highly
accurate approximation for vanilla attention. We process the queries in chunks,
and for each query, compute the top-\\(k\\) scores with respect to the keys. Our
approach offers several advantages: (a) its memory usage is linear in the input
size, similar to linear attention variants, such as Performer and RFA (b) it is
a drop-in replacement for vanilla attention that does not require any
corrective pre-training, and (c) it can also lead to significant memory savings
in the feed-forward layers after casting them into the familiar query-key-value
framework. We evaluate the quality of top-\\(k\\) approximation for multi-head
attention layers on the Long Range Arena Benchmark, and for feed-forward layers
of T5 and UnifiedQA on multiple QA datasets. We show our approach leads to
accuracy that is nearly-identical to vanilla attention in multiple setups
including training from scratch, fine-tuning, and zero-shot inference.
