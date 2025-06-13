---
layout: publication
title: 'Zero Token-driven Deep Thinking In Llms: Unlocking The Full Potential Of Existing Parameters Via Cyclic Refinement'
authors: Guanghao Li, Wenhao Jiang, Li Shen, Ming Tang, Chun Yuan
conference: "Arxiv"
year: 2025
bibkey: li2025zero
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.12214'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
Resource limitations often constrain the parameter counts of Large Language
Models (LLMs), hindering their performance. While existing methods employ
parameter sharing to reuse the same parameter set under fixed budgets, such
approaches typically force each layer to assume multiple roles with a
predetermined number of iterations, restricting efficiency and adaptability. In
this work, we propose the Zero Token Transformer (ZTT), which features a
head-tail decoupled parameter cycling method. We disentangle the first (head)
and last (tail) layers from parameter cycling and iteratively refine only the
intermediate layers. Furthermore, we introduce a Zero-Token Mechanism, an
internal architectural component rather than an input token, to guide
layer-specific computation. At each cycle, the model retrieves a zero token
(with trainable key values) from a Zero-Token Pool, integrating it alongside
regular tokens in the attention mechanism. The corresponding attention scores
not only reflect each layer's computational importance but also enable dynamic
early exits without sacrificing overall model accuracy. Our approach achieves
superior performance under tight parameter budgets, effectively reduces
computational overhead via early exits, and can be readily applied to fine-tune
existing pre-trained models for enhanced efficiency and adaptability.
