---
layout: publication
title: 'Large Language Model Compression Via The Nested Activation-aware Decomposition'
authors: Jun Lu, Tianyi Xu, Bill Ding, David Li, Yu Kang
conference: "Arxiv"
year: 2025
bibkey: lu2025large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17101"}
tags: ['Training Techniques', 'Quantization', 'Efficiency and Optimization', 'Tools']
---
In this paper, we tackle the critical challenge of compressing large language
models (LLMs) to facilitate their practical deployment and broader adoption. We
introduce a novel post-training compression paradigm that focuses on low-rank
decomposition of LLM weights. Our analysis identifies two main challenges in
this task: the variability in LLM activation distributions and handling unseen
activations from different datasets and models.
  To address these challenges, we propose a nested activation-aware framework
(NSVD) for LLMs, a training-free approach designed to enhance the accuracy of
low-rank decompositions by managing activation outliers through transforming
the weight matrix based on activation distribution and the original weight
matrix. This method allows for the absorption of outliers into the transformed
weight matrix, improving decomposition accuracy. Our comprehensive evaluation
across eight datasets and six models from three distinct LLM families
demonstrates the superiority of NSVD over current state-of-the-art methods,
especially at medium to large compression ratios or in multilingual and
multitask settings.
