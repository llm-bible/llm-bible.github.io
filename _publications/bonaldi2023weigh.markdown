---
layout: publication
title: 'Weigh Your Own Words: Improving Hate Speech Counter Narrative Generation Via Attention Regularization'
authors: Helena Bonaldi, Giuseppe Attanasio, Debora Nozza, Marco Guerini
conference: "Arxiv"
year: 2023
bibkey: bonaldi2023weigh
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.02311'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent computational approaches for combating online hate speech involve the
automatic generation of counter narratives by adapting Pretrained
Transformer-based Language Models (PLMs) with human-curated data. This process,
however, can produce in-domain overfitting, resulting in models generating
acceptable narratives only for hatred similar to training data, with little
portability to other targets or to real-world toxic language. This paper
introduces novel attention regularization methodologies to improve the
generalization capabilities of PLMs for counter narratives generation.
Overfitting to training-specific terms is then discouraged, resulting in more
diverse and richer narratives. We experiment with two attention-based
regularization techniques on a benchmark English dataset. Regularized models
produce better counter narratives than state-of-the-art approaches in most
cases, both in terms of automatic metrics and human evaluation, especially when
hateful targets are not present in the training data. This work paves the way
for better and more flexible counter-speech generation models, a task for which
datasets are highly challenging to produce.
