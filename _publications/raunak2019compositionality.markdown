---
layout: publication
title: 'On Compositionality In Neural Machine Translation'
authors: Vikas Raunak, Vaibhav Kumar, Florian Metze
conference: "Arxiv"
year: 2019
bibkey: raunak2019compositionality
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1911.01497'}
tags: ['Pre-Training', 'Applications', 'Training Techniques']
---
We investigate two specific manifestations of compositionality in Neural
Machine Translation (NMT) : (1) Productivity - the ability of the model to
extend its predictions beyond the observed length in training data and (2)
Systematicity - the ability of the model to systematically recombine known
parts and rules. We evaluate a standard Sequence to Sequence model on tests
designed to assess these two properties in NMT. We quantitatively demonstrate
that inadequate temporal processing, in the form of poor encoder
representations is a bottleneck for both Productivity and Systematicity. We
propose a simple pre-training mechanism which alleviates model performance on
the two properties and leads to a significant improvement in BLEU scores.
