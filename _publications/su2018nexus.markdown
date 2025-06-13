---
layout: publication
title: 'NEXUS Network: Connecting The Preceding And The Following In Dialogue Generation'
authors: Hui Su, Xiaoyu Shen, Wenjie Li, Dietrich Klakow
conference: "Arxiv"
year: 2018
bibkey: su2018nexus
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1810.00671'}
tags: ['Applications']
---
Sequence-to-Sequence (seq2seq) models have become overwhelmingly popular in
building end-to-end trainable dialogue systems. Though highly efficient in
learning the backbone of human-computer communications, they suffer from the
problem of strongly favoring short generic responses. In this paper, we argue
that a good response should smoothly connect both the preceding dialogue
history and the following conversations. We strengthen this connection through
mutual information maximization. To sidestep the non-differentiability of
discrete natural language tokens, we introduce an auxiliary continuous code
space and map such code space to a learnable prior distribution for generation
purpose. Experiments on two dialogue datasets validate the effectiveness of our
model, where the generated responses are closely related to the dialogue
context and lead to more interactive conversations.
