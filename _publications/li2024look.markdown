---
layout: publication
title: 'Look Within, Why Llms Hallucinate: A Causal Perspective'
authors: He Li, Haoang Chi, Mingyu Liu, Wenjing Yang
conference: "Arxiv"
year: 2024
bibkey: li2024look
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.10153'}
tags: ['Attention Mechanism', 'Transformer', 'Applications', 'Model Architecture', 'Pretraining Methods']
---
The emergence of large language models (LLMs) is a milestone in generative
artificial intelligence, achieving significant success in text comprehension
and generation tasks. Despite the tremendous success of LLMs in many downstream
tasks, they suffer from severe hallucination problems, posing significant
challenges to the practical applications of LLMs. Most of the works about LLMs'
hallucinations focus on data quality. Self-attention is a core module in
transformer-based LLMs, while its potential relationship with LLMs'
hallucination has been hardly investigated. To fill this gap, we study this
problem from a causal perspective. We propose a method to intervene in LLMs'
self-attention layers and maintain their structures and sizes intact.
Specifically, we disable different self-attention layers in several popular
open-source LLMs and then compare their degrees of hallucination with the
original ones. We evaluate the intervened LLMs on hallucination assessment
benchmarks and conclude that disabling some specific self-attention layers in
the front or tail of the LLMs can alleviate hallucination issues. The study
paves a new way for understanding and mitigating LLMs' hallucinations.
