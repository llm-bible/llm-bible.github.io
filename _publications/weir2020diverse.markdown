---
layout: publication
title: 'COD3S: Diverse Generation With Discrete Semantic Signatures'
authors: Nathaniel Weir, João Sedoc, Benjamin Van Durme
conference: "Arxiv"
year: 2020
bibkey: weir2020diverse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.02882"}
tags: ['Reinforcement Learning']
---
We present COD3S, a novel method for generating semantically diverse
sentences using neural sequence-to-sequence (seq2seq) models. Conditioned on an
input, seq2seq models typically produce semantically and syntactically
homogeneous sets of sentences and thus perform poorly on one-to-many sequence
generation tasks. Our two-stage approach improves output diversity by
conditioning generation on locality-sensitive hash (LSH)-based semantic
sentence codes whose Hamming distances highly correlate with human judgments of
semantic textual similarity. Though it is generally applicable, we apply COD3S
to causal generation, the task of predicting a proposition's plausible causes
or effects. We demonstrate through automatic and human evaluation that
responses produced using our method exhibit improved diversity without
degrading task performance.
