---
layout: publication
title: 'A Simple Contrastive Learning Objective For Alleviating Neural Text Degeneration'
authors: Shaojie Jiang, Ruqing Zhang, Svitlana Vakulenko, Maarten De Rijke
conference: "Arxiv"
year: 2022
bibkey: jiang2022simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2205.02517"}
tags: ['Training Techniques', 'GPT', 'Language Modeling', 'Pretraining Methods']
---
The cross-entropy objective has proved to be an all-purpose training
objective for autoregressive language models (LMs). However, without
considering the penalization of problematic tokens, LMs trained using
cross-entropy exhibit text degeneration. To address this, unlikelihood training
has been proposed to reduce the probability of unlikely tokens predicted by
LMs. But unlikelihood does not consider the relationship between the label
tokens and unlikely token candidates, thus showing marginal improvements in
degeneration. We propose a new contrastive token learning objective that
inherits the advantages of cross-entropy and unlikelihood training and avoids
their limitations. The key idea is to teach a LM to generate high probabilities
for label tokens and low probabilities of negative candidates. Comprehensive
experiments on language modeling and open-domain dialogue generation tasks show
that the proposed contrastive token objective yields much less repetitive
texts, with a higher generation quality than baseline approaches, achieving the
new state-of-the-art performance on text degeneration.
