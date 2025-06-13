---
layout: publication
title: 'Skipdecode: Autoregressive Skip Decoding With Batching And Caching For Efficient LLM Inference'
authors: Luciano Del Corro, Allie Del Giorno, Sahaj Agarwal, Bin Yu, Ahmed Awadallah, Subhabrata Mukherjee
conference: "Arxiv"
year: 2023
bibkey: delcorro2023autoregressive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.02628'}
tags: ['Language Modeling', 'Efficiency and Optimization', 'GPT', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Autoregressive large language models (LLMs) have made remarkable progress in
various natural language generation tasks. However, they incur high computation
cost and latency resulting from the autoregressive token-by-token generation.
To address this issue, several approaches have been proposed to reduce
computational cost using early-exit strategies. These strategies enable faster
text generation using reduced computation without applying the full computation
graph to each token. While existing token-level early exit methods show
promising results for online inference, they cannot be readily applied for
batch inferencing and Key-Value caching. This is because they have to wait
until the last token in a batch exits before they can stop computing. This
severely limits the practical application of such techniques. In this paper, we
propose a simple and effective token-level early exit method, SkipDecode,
designed to work seamlessly with batch inferencing and KV caching. It overcomes
prior constraints by setting up a singular exit point for every token in a
batch at each sequence position. It also guarantees a monotonic decrease in
exit points, thereby eliminating the need to recompute KV Caches for preceding
tokens. Rather than terminating computation prematurely as in prior works, our
approach bypasses lower to middle layers, devoting most of the computational
resources to upper layers, allowing later tokens to benefit from the compute
expenditure by earlier tokens. Our experimental results show that SkipDecode
can obtain 2x to 5x inference speedups with negligible regression across a
variety of tasks. This is achieved using OPT models of 1.3 billion and 6.7
billion parameters, all the while being directly compatible with batching and
KV caching optimization techniques.
