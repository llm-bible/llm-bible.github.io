---
layout: publication
title: 'FIRP: Faster LLM Inference Via Future Intermediate Representation Prediction'
authors: Pengfei Wu, Jiahao Liu, Zhuocheng Gong, Qifan Wang, Jinpeng Li, Jingang Wang, Xunliang Cai, Dongyan Zhao
conference: "NLPCC2024"
year: 2024
bibkey: wu2024faster
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.20488"}
tags: ['Uncategorized']
---
Recent advancements in Large Language Models (LLMs) have shown remarkable
performance across a wide range of tasks. Despite this, the auto-regressive
nature of LLM decoding, which generates only a single token per forward
propagation, fails to fully exploit the parallel computational power of GPUs,
leading to considerable latency. To address this, we introduce a novel
speculative decoding method named FIRP which generates multiple tokens instead
of one at each decoding step. We achieve this by predicting the intermediate
hidden states of future tokens (tokens have not been decoded yet) and then
using these pseudo hidden states to decode future tokens, specifically, these
pseudo hidden states are predicted with simple linear transformation in
intermediate layers of LLMs. Once predicted, they participate in the
computation of all the following layers, thereby assimilating richer semantic
information. As the layers go deeper, the semantic gap between pseudo and real
hidden states is narrowed and it becomes feasible to decode future tokens with
high accuracy. To validate the effectiveness of FIRP, we conduct extensive
experiments, showing a speedup ratio of 1.9x-3x in several models and datasets,
analytical experiments also prove our motivations.
