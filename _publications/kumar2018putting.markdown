---
layout: publication
title: Putting The Horse Before The Cart:a Generator-evaluator Framework For Question
  Generation From Text
authors: Vishwajeet Kumar, Ganesh Ramakrishnan, Yuan-fang Li
conference: Arxiv
year: 2018
citations: 15
bibkey: kumar2018putting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1808.04961'}]
tags: [RAG, Reinforcement Learning]
---
Automatic question generation (QG) is a useful yet challenging task in NLP.
Recent neural network-based approaches represent the state-of-the-art in this
task. In this work, we attempt to strengthen them significantly by adopting a
holistic and novel generator-evaluator framework that directly optimizes
objectives that reward semantics and structure. The \{\it generator\} is a
sequence-to-sequence model that incorporates the \{\it structure\} and \{\it
semantics\} of the question being generated. The generator predicts an answer in
the passage that the question can pivot on. Employing the copy and coverage
mechanisms, it also acknowledges other contextually important (and possibly
rare) keywords in the passage that the question needs to conform to, while not
redundantly repeating words. The \{\it evaluator\} model evaluates and assigns a
reward to each predicted question based on its conformity to the \{\it
structure\} of ground-truth questions. We propose two novel QG-specific reward
functions for text conformity and answer conformity of the generated question.
The evaluator also employs structure-sensitive rewards based on evaluation
measures such as BLEU, GLEU, and ROUGE-L, which are suitable for QG. In
contrast, most of the previous works only optimize the cross-entropy loss,
which can induce inconsistencies between training (objective) and testing
(evaluation) measures. Our evaluation shows that our approach significantly
outperforms state-of-the-art systems on the widely-used SQuAD benchmark as per
both automatic and human evaluation.