---
layout: publication
title: 'SLM: Learning A Discourse Language Representation With Sentence Unshuffling'
authors: Haejun Lee, Drew A. Hudson, Kangwook Lee, Christopher D. Manning
conference: "Arxiv"
year: 2020
bibkey: lee2020learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.16249"}
tags: ['Transformer', 'Pre-Training', 'RAG', 'Language Modeling', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
We introduce Sentence-level Language Modeling, a new pre-training objective
for learning a discourse language representation in a fully self-supervised
manner. Recent pre-training methods in NLP focus on learning either bottom or
top-level language representations: contextualized word representations derived
from language model objectives at one extreme and a whole sequence
representation learned by order classification of two given textual segments at
the other. However, these models are not directly encouraged to capture
representations of intermediate-size structures that exist in natural languages
such as sentences and the relationships among them. To that end, we propose a
new approach to encourage learning of a contextualized sentence-level
representation by shuffling the sequence of input sentences and training a
hierarchical transformer model to reconstruct the original ordering. Through
experiments on downstream tasks such as GLUE, SQuAD, and DiscoEval, we show
that this feature of our model improves the performance of the original BERT by
large margins.
