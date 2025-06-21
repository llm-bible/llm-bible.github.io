---
layout: publication
title: Scalable And Efficient Moe Training For Multitask Multilingual Models
authors: Young Jin Kim et al.
conference: Arxiv
year: 2021
citations: 29
bibkey: kim2021scalable
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.10465'}]
tags: [Efficiency and Optimization, Fine-Tuning, RAG, Reinforcement Learning, Tools,
  Model Architecture]
---
The Mixture of Experts (MoE) models are an emerging class of sparsely
activated deep learning models that have sublinear compute costs with respect
to their parameters. In contrast with dense models, the sparse architecture of
MoE offers opportunities for drastically growing model size with significant
accuracy gain while consuming much lower compute budget. However, supporting
large scale MoE training also has its own set of system and modeling
challenges. To overcome the challenges and embrace the opportunities of MoE, we
first develop a system capable of scaling MoE models efficiently to trillions
of parameters. It combines multi-dimensional parallelism and heterogeneous
memory technologies harmoniously with MoE to empower 8x larger models on the
same hardware compared with existing work. Besides boosting system efficiency,
we also present new training methods to improve MoE sample efficiency and
leverage expert pruning strategy to improve inference time efficiency. By
combining the efficient system and training methods, we are able to
significantly scale up large multitask multilingual models for language
generation which results in a great improvement in model accuracy. A model
trained with 10 billion parameters on 50 languages can achieve state-of-the-art
performance in Machine Translation (MT) and multilingual natural language
generation tasks. The system support of efficient MoE training has been
implemented and open-sourced with the DeepSpeed library.