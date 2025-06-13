---
layout: publication
title: 'Spacebyte: Towards Deleting Tokenization From Large Language Modeling'
authors: Kevin Slagle
conference: "Arxiv"
year: 2024
bibkey: slagle2024towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.14408'}
tags: ['Language Modeling', 'Transformer', 'Security', 'Training Techniques', 'Model Architecture', 'GPT', 'Ethics and Bias', 'Tokenization', 'Pretraining Methods']
---
Tokenization is widely used in large language models because it significantly
improves performance. However, tokenization imposes several disadvantages, such
as performance biases, increased adversarial vulnerability, decreased
character-level modeling performance, and increased modeling complexity. To
address these disadvantages without sacrificing performance, we propose
SpaceByte, a novel byte-level decoder architecture that closes the performance
gap between byte-level and subword autoregressive language modeling. SpaceByte
consists of a byte-level Transformer model, but with extra larger transformer
blocks inserted in the middle of the layers. We find that performance is
significantly improved by applying these larger blocks only after certain
bytes, such as space characters, which typically denote word boundaries. Our
experiments show that for a fixed training and inference compute budget,
SpaceByte outperforms other byte-level architectures and roughly matches the
performance of tokenized Transformer architectures.
