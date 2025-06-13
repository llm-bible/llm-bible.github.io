---
layout: publication
title: 'Towards Neural Machine Translation With Latent Tree Attention'
authors: James Bradbury, Richard Socher
conference: "Arxiv"
year: 2017
bibkey: bradbury2017towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1709.01915"}
tags: ['Agentic', 'Model Architecture', 'Reinforcement Learning', 'Applications', 'Attention Mechanism']
---
Building models that take advantage of the hierarchical structure of language
without a priori annotation is a longstanding goal in natural language
processing. We introduce such a model for the task of machine translation,
pairing a recurrent neural network grammar encoder with a novel attentional
RNNG decoder and applying policy gradient reinforcement learning to induce
unsupervised tree structures on both the source and target. When trained on
character-level datasets with no explicit segmentation or parse annotation, the
model learns a plausible segmentation and shallow parse, obtaining performance
close to an attentional baseline.
