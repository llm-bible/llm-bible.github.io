---
layout: publication
title: 'Parallel Sentence-level Explanation Generation For Real-world Low-resource Scenarios'
authors: Yan Liu, Xiaokang Chen, Qi Dai
conference: "Arxiv"
year: 2023
bibkey: liu2023parallel
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.10707"}
tags: ['Training Techniques', 'Reinforcement Learning', 'GPT', 'Pretraining Methods', 'Interpretability and Explainability']
---
In order to reveal the rationale behind model predictions, many works have
exploited providing explanations in various forms. Recently, to further
guarantee readability, more and more works turn to generate sentence-level
human language explanations. However, current works pursuing sentence-level
explanations rely heavily on annotated training data, which limits the
development of interpretability to only a few tasks. As far as we know, this
paper is the first to explore this problem smoothly from weak-supervised
learning to unsupervised learning. Besides, we also notice the high latency of
autoregressive sentence-level explanation generation, which leads to
asynchronous interpretability after prediction. Therefore, we propose a
non-autoregressive interpretable model to facilitate parallel explanation
generation and simultaneous prediction. Through extensive experiments on
Natural Language Inference task and Spouse Prediction task, we find that users
are able to train classifiers with comparable performance \\(10-15\times\\) faster
with parallel explanation generation using only a few or no annotated training
data.
