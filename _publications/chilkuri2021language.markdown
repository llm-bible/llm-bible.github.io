---
layout: publication
title: Language Modeling using LMUs 10x Better Data Efficiency or Improved Scaling Compared to Transformers
authors: Chilkuri Narsimha, Hunsberger Eric, Voelker Aaron, Malik Gurshaant, Eliasmith Chris
conference: "Arxiv"
year: 2021
bibkey: chilkuri2021language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.02402"}
tags: ['ARXIV', 'Language Modeling', 'Model Architecture', 'Transformer']
---
Recent studies have demonstrated that the performance of transformers on the task of language modeling obeys a power-law relationship with model size over six orders of magnitude. While transformers exhibit impressive scaling their performance hinges on processing large amounts of data and their computational and memory requirements grow quadratically with sequence length. Motivated by these considerations we construct a Legendre Memory Unit based model that introduces a general prior for sequence processing and exhibits an O(n) and O(n ln n) (or better) dependency for memory and computation respectively. Over three orders of magnitude we show that our new architecture attains the same accuracy as transformers with 10x fewer tokens. We also show that for the same amount of training our model improves the loss over transformers about as much as transformers improve over LSTMs. Additionally we demonstrate that adding global self-attention complements our architecture and the augmented model improves performance even further.
