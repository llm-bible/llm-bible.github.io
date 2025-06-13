---
layout: publication
title: 'Compressing KV Cache For Long-context LLM Inference With Inter-layer Attention Similarity'
authors: Da Ma, Lu Chen, Situo Zhang, Yuxun Miao, Su Zhu, Zhi Chen, Hongshen Xu, Hanqi Li, Shuai Fan, Lei Pan, Kai Yu
conference: "Arxiv"
year: 2024
bibkey: ma2024compressing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.02252'}
tags: ['Attention Mechanism', 'Language Modeling', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Applications', 'Reinforcement Learning']
---
The increasing context window size in Large Language Models (LLMs), such as
the GPT and LLaMA series, has improved their ability to tackle complex,
long-text tasks, but at the cost of inference efficiency, particularly
regarding memory and computational complexity. Existing methods, including
selective token retention and window-based attention, improve efficiency but
risk discarding important tokens needed for future text generation. In this
paper, we propose an approach that enhances LLM efficiency without token loss
by reducing the memory and computational load of less important tokens, rather
than discarding them.We address two challenges: 1) investigating the
distribution of important tokens in the context, discovering recent tokens are
more important than distant tokens in context, and 2) optimizing resources for
distant tokens by sharing attention scores across layers. The experiments show
that our method saves \\(35%\\) KV cache without compromising the performance.
