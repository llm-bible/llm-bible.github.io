---
layout: publication
title: 'Grithopper: Decomposition-free Multi-hop Dense Retrieval'
authors: Justus-jonas Erker, Nils Reimers, Iryna Gurevych
conference: "Arxiv"
year: 2025
bibkey: erker2025decomposition
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.07519'}
tags: ['Language Modeling', 'Training Techniques', 'Applications', 'GPT', 'Pretraining Methods']
---
Decomposition-based multi-hop retrieval methods rely on many autoregressive
steps to break down complex queries, which breaks end-to-end differentiability
and is computationally expensive. Decomposition-free methods tackle this, but
current decomposition-free approaches struggle with longer multi-hop problems
and generalization to out-of-distribution data. To address these challenges, we
introduce GRITHopper-7B, a novel multi-hop dense retrieval model that achieves
state-of-the-art performance on both in-distribution and out-of-distribution
benchmarks. GRITHopper combines generative and representational instruction
tuning by integrating causal language modeling with dense retrieval training.
Through controlled studies, we find that incorporating additional context after
the retrieval process, referred to as post-retrieval language modeling,
enhances dense retrieval performance. By including elements such as final
answers during training, the model learns to better contextualize and retrieve
relevant information. GRITHopper-7B offers a robust, scalable, and
generalizable solution for multi-hop dense retrieval, and we release it to the
community for future research and applications requiring multi-hop reasoning
and retrieval capabilities.
