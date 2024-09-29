---
layout: publication
title: "Relational Memory Augmented Language Models"
authors: Liu Qi, Yogatama Dani, Blunsom Phil
conference: "Arxiv"
year: 2022
bibkey: liu2022relational
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2201.09680"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Pretraining Methods']
---
We present a memory-augmented approach to condition an autoregressive language model on a knowledge graph. We represent the graph as a collection of relation triples and retrieve relevant relations for a given context to improve text generation. Experiments on WikiText-103 WMT19 and enwik8 English datasets demonstrate that our approach produces a better language model in terms of perplexity and bits per character. We also show that relational memory improves coherence is complementary to token-based memory and enables causal interventions. Our model provides a simple yet effective way to combine an autoregressive language model with a knowledge graph for a more coherent and logical generation.
