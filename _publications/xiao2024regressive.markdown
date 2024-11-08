---
layout: publication
title: 'Clover: Regressive Lightweight Speculative Decoding With Sequential Knowledge'
authors: Xiao Bin, Shi Chunan, Nie Xiaonan, Yang Fan, Deng Xiangwei, Su Lei, Chen Weipeng, Cui Bin
conference: "Arxiv"
year: 2024
bibkey: xiao2024regressive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00263"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Training Techniques']
---
Large language models (LLMs) suffer from low efficiency as the mismatch
between the requirement of auto-regressive decoding and the design of most
contemporary GPUs. Specifically, billions to trillions of parameters must be
loaded to the GPU cache through its limited memory bandwidth for computation,
but only a small batch of tokens is actually computed. Consequently, the GPU
spends most of its time on memory transfer instead of computation. Recently,
parallel decoding, a type of speculative decoding algorithms, is becoming more
popular and has demonstrated impressive efficiency improvement in generation.
It introduces extra decoding heads to large models, enabling them to predict
multiple subsequent tokens simultaneously and verify these candidate
continuations in a single decoding step. However, this approach deviates from
the training objective of next token prediction used during pre-training,
resulting in a low hit rate for candidate tokens. In this paper, we propose a
new speculative decoding algorithm, Clover, which integrates sequential
knowledge into the parallel decoding process. This enhancement improves the hit
rate of speculators and thus boosts the overall efficiency. Clover transmits
the sequential knowledge from pre-speculated tokens via the Regressive
Connection, then employs an Attention Decoder to integrate these speculated
tokens. Additionally, Clover incorporates an Augmenting Block that modifies the
hidden states to better align with the purpose of speculative generation rather
than next token prediction. The experiment results demonstrate that Clover
outperforms the baseline by up to 91% on Baichuan-Small and 146% on
Baichuan-Large, respectively, and exceeds the performance of the previously
top-performing method, Medusa, by up to 37% on Baichuan-Small and 57% on
Baichuan-Large, respectively.
