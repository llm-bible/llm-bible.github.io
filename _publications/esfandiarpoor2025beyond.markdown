---
layout: publication
title: 'Beyond Contrastive Learning: Synthetic Data Enables List-wise Training With Multiple Levels Of Relevance'
authors: Reza Esfandiarpoor, George Zerveas, Ruochen Zhang, Macton Mgonzo, Carsten Eickhoff, Stephen H. Bach
conference: "Arxiv"
year: 2025
bibkey: esfandiarpoor2025beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.23239'}
tags: ['Reinforcement Learning', 'Applications', 'Training Techniques', 'Pretraining Methods']
---
Recent advancements in large language models (LLMs) have allowed the
augmentation of information retrieval (IR) pipelines with synthetic data in
various ways. Yet, the main training paradigm remains: contrastive learning
with binary relevance labels and the InfoNCE loss, where one positive document
is compared against one or more negatives. This objective treats all documents
that are not explicitly annotated as relevant on an equally negative footing,
regardless of their actual degree of relevance, thus (a) missing subtle nuances
that are useful for ranking and (b) being susceptible to annotation noise. To
overcome this limitation, in this work we forgo real training documents and
annotations altogether and use open-source LLMs to directly generate synthetic
documents that answer real user queries according to several different levels
of relevance. This fully synthetic ranking context of graduated relevance,
together with an appropriate list-wise loss (Wasserstein distance), enables us
to train dense retrievers in a way that better captures the ranking task.
Experiments on various IR datasets show that our proposed approach outperforms
conventional training with InfoNCE by a large margin. Without using any real
documents for training, our dense retriever significantly outperforms the same
retriever trained through self-supervision. More importantly, it matches the
performance of the same retriever trained on real, labeled training documents
of the same dataset, while being more robust to distribution shift and clearly
outperforming it when evaluated zero-shot on the BEIR dataset collection.
