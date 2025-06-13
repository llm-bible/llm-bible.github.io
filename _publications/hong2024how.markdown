---
layout: publication
title: 'How Transformers Solve Propositional Logic Problems: A Mechanistic Analysis'
authors: Guan Zhe Hong, Nishanth Dikkala, Enming Luo, Cyrus Rashtchian, Xin Wang, Rina Panigrahy
conference: "Arxiv"
year: 2024
bibkey: hong2024how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.04105'}
tags: ['Attention Mechanism', 'Transformer', 'Training Techniques', 'Model Architecture', 'Pretraining Methods']
---
Large language models (LLMs) have shown amazing performance on tasks that
require planning and reasoning. Motivated by this, we investigate the internal
mechanisms that underpin a network's ability to perform complex logical
reasoning. We first construct a synthetic propositional logic problem that
serves as a concrete test-bed for network training and evaluation. Crucially,
this problem demands nontrivial planning to solve. We perform our study on two
fronts. First, we pursue an understanding of precisely how a three-layer
transformer, trained from scratch and attains perfect test accuracy, solves
this problem. We are able to identify certain "planning" and "reasoning"
mechanisms in the network that necessitate cooperation between the attention
blocks to implement the desired logic. Second, we study how pretrained LLMs,
namely Mistral-7B and Gemma-2-9B, solve this problem. We characterize their
reasoning circuits through causal intervention experiments, providing necessity
and sufficiency evidence for the circuits. We find evidence suggesting that the
two models' latent reasoning strategies are surprisingly similar, and
human-like. Overall, our work systemically uncovers novel aspects of small and
large transformers, and continues the study of how they plan and reason.
