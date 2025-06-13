---
layout: publication
title: 'Parallel Decoding Via Hidden Transfer For Lossless Large Language Model Acceleration'
authors: Pengfei Wu, Jiahao Liu, Zhuocheng Gong, Qifan Wang, Jinpeng Li, Jingang Wang, Xunliang Cai, Dongyan Zhao
conference: "Arxiv"
year: 2024
bibkey: wu2024parallel
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.12022'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'GPT', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) have recently shown remarkable performance
across a wide range of tasks. However, the substantial number of parameters in
LLMs contributes to significant latency during model inference. This is
particularly evident when utilizing autoregressive decoding methods, which
generate one token in a single forward process, thereby not fully capitalizing
on the parallel computing capabilities of GPUs. In this paper, we propose a
novel parallel decoding approach, namely \textit\{hidden transfer\}, which
decodes multiple successive tokens simultaneously in a single forward pass. The
idea is to transfer the intermediate hidden states of the previous context to
the \textit\{pseudo\} hidden states of the future tokens to be generated, and
then the pseudo hidden states will pass the following transformer layers
thereby assimilating more semantic information and achieving superior
predictive accuracy of the future tokens.
  Besides, we use the novel tree attention mechanism to simultaneously generate
and verify multiple candidates of output sequences, which ensure the lossless
generation and further improves the generation efficiency of our method.
Experiments demonstrate the effectiveness of our method. We conduct a lot of
analytic experiments to prove our motivation. In terms of acceleration metrics,
we outperform all the single-model acceleration techniques, including Medusa
and Self-Speculative decoding.
