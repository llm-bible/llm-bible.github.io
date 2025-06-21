---
layout: publication
title: 'BGE M3-embedding: Multi-lingual, Multi-functionality, Multi-granularity Text
  Embeddings Through Self-knowledge Distillation'
authors: Jianlv Chen et al.
conference: Arxiv
year: 2024
citations: 72
bibkey: chen2024bge
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.03216'}, {name: Code,
    url: 'https://github.com/FlagOpen/FlagEmbedding'}]
tags: [Distillation, Applications, Efficiency and Optimization]
---
In this paper, we present a new embedding model, called M3-Embedding, which
is distinguished for its versatility in Multi-Linguality, Multi-Functionality,
and Multi-Granularity. It can support more than 100 working languages, leading
to new state-of-the-art performances on multi-lingual and cross-lingual
retrieval tasks. It can simultaneously perform the three common retrieval
functionalities of embedding model: dense retrieval, multi-vector retrieval,
and sparse retrieval, which provides a unified model foundation for real-world
IR applications. It is able to process inputs of different granularities,
spanning from short sentences to long documents of up to 8192 tokens. The
effective training of M3-Embedding involves the following technical
contributions. We propose a novel self-knowledge distillation approach, where
the relevance scores from different retrieval functionalities can be integrated
as the teacher signal to enhance the training quality. We also optimize the
batching strategy, enabling a large batch size and high training throughput to
ensure the discriminativeness of embeddings. To the best of our knowledge,
M3-Embedding is the first embedding model which realizes such a strong
versatility. The model and code will be publicly available at
https://github.com/FlagOpen/FlagEmbedding.