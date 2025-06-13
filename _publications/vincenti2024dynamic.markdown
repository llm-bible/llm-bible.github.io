---
layout: publication
title: 'Dynamic Vocabulary Pruning In Early-exit Llms'
authors: Jort Vincenti, Karim Abdel Sadek, Joan Velja, Matteo Nulli, Metod Jazbec
conference: "NeurIPS 2024 ENLSP Workshop"
year: 2024
bibkey: vincenti2024dynamic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.18952'}
tags: ['Reinforcement Learning', 'Pruning', 'Efficiency and Optimization']
---
Increasing the size of large language models (LLMs) has been shown to lead to
better performance. However, this comes at the cost of slower and more
expensive inference. Early-exiting is a promising approach for improving the
efficiency of LLM inference by enabling next token prediction at intermediate
layers. Yet, the large vocabulary size in modern LLMs makes the confidence
estimation required for exit decisions computationally expensive, diminishing
the efficiency gains. To address this, we propose dynamically pruning the
vocabulary at test time for each token. Specifically, the vocabulary is pruned
at one of the initial layers, and the smaller vocabulary is then used
throughout the rest of the forward pass. Our experiments demonstrate that such
post-hoc dynamic vocabulary pruning improves the efficiency of confidence
estimation in early-exit LLMs while maintaining competitive performance.
