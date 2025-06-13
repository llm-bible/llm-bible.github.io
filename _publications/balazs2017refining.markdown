---
layout: publication
title: 'Refining Raw Sentence Representations For Textual Entailment Recognition Via Attention'
authors: Jorge A. Balazs, Edison Marrese-taylor, Pablo Loyola, Yutaka Matsuo
conference: "Arxiv"
year: 2017
bibkey: balazs2017refining
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1707.03103'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture']
---
In this paper we present the model used by the team Rivercorners for the 2017
RepEval shared task. First, our model separately encodes a pair of sentences
into variable-length representations by using a bidirectional LSTM. Later, it
creates fixed-length raw representations by means of simple aggregation
functions, which are then refined using an attention mechanism. Finally it
combines the refined representations of both sentences into a single vector to
be used for classification. With this model we obtained test accuracies of
72.057% and 72.055% in the matched and mismatched evaluation tracks
respectively, outperforming the LSTM baseline, and obtaining performances
similar to a model that relies on shared information between sentences (ESIM).
When using an ensemble both accuracies increased to 72.247% and 72.827%
respectively.
