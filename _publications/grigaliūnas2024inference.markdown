---
layout: publication
title: 'Inference Acceleration For Large Language Models Using "stairs" Assisted Greedy Generation'
authors: Domas Grigaliūnas, Mantas Lukoševičius
conference: "Arxiv"
year: 2024
bibkey: grigaliūnas2024inference
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.19947'}
tags: ['Language Modeling', 'Applications']
---
Large Language Models (LLMs) with billions of parameters are known for their
impressive predicting capabilities but require lots of resources to run. With
their massive rise in popularity, even a small reduction in required resources
could have an impact on environment. On the other hand, smaller models require
fewer resources but may sacrifice accuracy. In this work, we are proposing an
implementation of ``stairs'' assisted greedy generation. It is a modified
assisted generation methodology that makes use of a smaller model's fast
generation, large model's batch prediction, and "stairs" validation in order to
achieve a speed up in prediction generation. Results show between 9.58 and
17.24 percent inference time reduction compared to a stand-alone large LLM
prediction in a text generation task without a loss in accuracy.
