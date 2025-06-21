---
layout: publication
title: Do Attention Heads In BERT Track Syntactic Dependencies?
authors: Phu Mon Htut, Jason Phang, Shikha Bordia, Samuel R. Bowman
conference: Arxiv
year: 2019
citations: 103
bibkey: htut2019do
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.12246'}]
tags: [Transformer, BERT, Fine-Tuning]
---
We investigate the extent to which individual attention heads in pretrained
transformer language models, such as BERT and RoBERTa, implicitly capture
syntactic dependency relations. We employ two methods---taking the maximum
attention weight and computing the maximum spanning tree---to extract implicit
dependency relations from the attention weights of each layer/head, and compare
them to the ground-truth Universal Dependency (UD) trees. We show that, for
some UD relation types, there exist heads that can recover the dependency type
significantly better than baselines on parsed English text, suggesting that
some self-attention heads act as a proxy for syntactic structure. We also
analyze BERT fine-tuned on two datasets---the syntax-oriented CoLA and the
semantics-oriented MNLI---to investigate whether fine-tuning affects the
patterns of their self-attention, but we do not observe substantial differences
in the overall dependency relations extracted using our methods. Our results
suggest that these models have some specialist attention heads that track
individual dependency types, but no generalist head that performs holistic
parsing significantly better than a trivial baseline, and that analyzing
attention weights directly may not reveal much of the syntactic knowledge that
BERT-style models are known to learn.