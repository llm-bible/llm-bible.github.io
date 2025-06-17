---
layout: publication
title: Fast Inference From Transformers Via Speculative Decoding
authors: Yaniv Leviathan, Matan Kalman, Yossi Matias
conference: Arxiv
year: 2022
citations: 19
bibkey: leviathan2022fast
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.17192'}]
tags: [GPT, Transformer, Language Modeling, Efficiency and Optimization]
---
Inference from large autoregressive models like Transformers is slow -
decoding K tokens takes K serial runs of the model. In this work we introduce
speculative decoding - an algorithm to sample from autoregressive models faster
without any changes to the outputs, by computing several tokens in parallel. At
the heart of our approach lie the observations that (1) hard language-modeling
tasks often include easier subtasks that can be approximated well by more
efficient models, and (2) using speculative execution and a novel sampling
method, we can make exact decoding from the large models faster, by running
them in parallel on the outputs of the approximation models, potentially
generating several tokens concurrently, and without changing the distribution.
Our method can accelerate existing off-the-shelf models without retraining or
architecture changes. We demonstrate it on T5-XXL and show a 2X-3X acceleration
compared to the standard T5X implementation, with identical outputs.