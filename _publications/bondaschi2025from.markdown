---
layout: publication
title: 'From Markov To Laplace: How Mamba In-context Learns Markov Chains'
authors: Marco Bondaschi, Nived Rajaraman, Xiuying Wei, Kannan Ramchandran, Razvan Pascanu, Caglar Gulcehre, Michael Gastpar, Ashok Vardhan Makkuva
conference: "Arxiv"
year: 2025
bibkey: bondaschi2025from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.10178'}
tags: ['Language Modeling', 'Transformer', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
While transformer-based language models have driven the AI revolution thus
far, their computational complexity has spurred growing interest in viable
alternatives, such as structured state space sequence models (SSMs) and
Selective SSMs. Among these, Mamba (S6) and its variant Mamba-2 have shown
remarkable inference speed ups over transformers while achieving comparable or
superior performance on complex language modeling tasks. However, despite these
architectural innovations and empirical successes, the fundamental learning
capabilities of Mamba remain poorly understood. In this paper, we address this
gap by studying in-context learning (ICL) on Markov chains and uncovering a
surprising phenomenon: unlike transformers, even a single-layer Mamba
efficiently learns the in-context Laplacian smoothing estimator, which is both
Bayes and minimax optimal, for all Markovian orders. To explain this, we
theoretically characterize the representation capacity of Mamba and reveal the
fundamental role of convolution in enabling it to represent the optimal
Laplacian smoothing. These theoretical insights align strongly with empirical
results and, to the best of our knowledge, represent the first formal
connection between Mamba and optimal statistical estimators. Finally, we
outline promising research directions inspired by these findings.
