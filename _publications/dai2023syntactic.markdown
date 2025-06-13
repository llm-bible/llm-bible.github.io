---
layout: publication
title: 'Syntactic Knowledge Via Graph Attention With BERT In Machine Translation'
authors: Yuqian Dai, Serge Sharoff, Marc De Kamps
conference: "Arxiv"
year: 2023
bibkey: dai2023syntactic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13413"}
tags: ['Model Architecture', 'Pretraining Methods', 'BERT', 'Transformer', 'Interpretability and Explainability', 'Applications', 'Attention Mechanism']
---
Although the Transformer model can effectively acquire context features via a
self-attention mechanism, deeper syntactic knowledge is still not effectively
modeled. To alleviate the above problem, we propose Syntactic knowledge via
Graph attention with BERT (SGB) in Machine Translation (MT) scenarios. Graph
Attention Network (GAT) and BERT jointly represent syntactic dependency feature
as explicit knowledge of the source language to enrich source language
representations and guide target language generation. Our experiments use gold
syntax-annotation sentences and Quality Estimation (QE) model to obtain
interpretability of translation quality improvement regarding syntactic
knowledge without being limited to a BLEU score. Experiments show that the
proposed SGB engines improve translation quality across the three MT tasks
without sacrificing BLEU scores. We investigate what length of source sentences
benefits the most and what dependencies are better identified by the SGB
engines. We also find that learning of specific dependency relations by GAT can
be reflected in the translation quality containing such relations and that
syntax on the graph leads to new modeling of syntactic aspects of source
sentences in the middle and bottom layers of BERT.
