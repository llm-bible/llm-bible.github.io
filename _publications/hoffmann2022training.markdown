---
layout: publication
title: Training Compute-optimal Large Language Models
authors: Jordan Hoffmann et al.
conference: Arxiv
year: 2022
citations: 452
bibkey: hoffmann2022training
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.15556'}]
tags: [GPT, Transformer, Fine-Tuning]
---
We investigate the optimal model size and number of tokens for training a
transformer language model under a given compute budget. We find that current
large language models are significantly undertrained, a consequence of the
recent focus on scaling language models whilst keeping the amount of training
data constant. By training over 400 language models ranging from 70 million to
over 16 billion parameters on 5 to 500 billion tokens, we find that for
compute-optimal training, the model size and the number of training tokens
should be scaled equally: for every doubling of model size the number of
training tokens should also be doubled. We test this hypothesis by training a
predicted compute-optimal model, Chinchilla, that uses the same compute budget
as Gopher but with 70B parameters and 4\\(\times\\) more more data. Chinchilla
uniformly and significantly outperforms Gopher (280B), GPT-3 (175B), Jurassic-1
(178B), and Megatron-Turing NLG (530B) on a large range of downstream
evaluation tasks. This also means that Chinchilla uses substantially less
compute for fine-tuning and inference, greatly facilitating downstream usage.
As a highlight, Chinchilla reaches a state-of-the-art average accuracy of 67.5%
on the MMLU benchmark, greater than a 7% improvement over Gopher.