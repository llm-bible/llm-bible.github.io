---
layout: publication
title: 'Gateloop: Fully Data-controlled Linear Recurrence For Sequence Modeling'
authors: Tobias Katsch
conference: "Arxiv"
year: 2023
bibkey: katsch2023fully
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.01927'}
tags: ['Attention Mechanism', 'Language Modeling', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
Linear Recurrence has proven to be a powerful tool for modeling long
sequences efficiently. In this work, we show that existing models fail to take
full advantage of its potential. Motivated by this finding, we develop
GateLoop, a foundational sequence model that generalizes linear recurrent
models such as S4, S5, LRU and RetNet, by employing data-controlled state
transitions. Utilizing this theoretical advance, GateLoop empirically
outperforms existing models for auto-regressive language modeling. Our method
comes with a low-cost \\(O(l)\\) recurrent mode and an efficient \\(O(l log_\{2\} l)\\)
parallel mode making use of highly optimized associative scan implementations.
Furthermore, we derive an \\(O(l^2)\\) surrogate attention mode, revealing
remarkable implications for Transformer and recently proposed architectures.
Specifically, we prove that our approach can be interpreted as providing
data-controlled relative-positional information to Attention. While many
existing models solely rely on data-controlled cumulative sums for context
aggregation, our findings suggest that incorporating data-controlled complex
cumulative products may be a crucial step towards more powerful sequence
models.
