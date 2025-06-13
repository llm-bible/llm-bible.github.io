---
layout: publication
title: 'SMART-RAG: Selection Using Determinantal Matrices For Augmented Retrieval'
authors: Jiatao Li, Xinyu Hu, Xiaojun Wan
conference: "Arxiv"
year: 2024
bibkey: li2024smart
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.13992'}
tags: ['RAG', 'Training Techniques', 'Applications', 'Tools', 'Reinforcement Learning']
---
Retrieval-Augmented Generation (RAG) has greatly improved large language
models (LLMs) by enabling them to generate accurate, contextually grounded
responses through the integration of external information. However,
conventional RAG approaches, which prioritize top-ranked documents based solely
on query-context relevance, often introduce redundancy and conflicting
information. This issue is particularly evident in unsupervised retrieval
settings, where there are no mechanisms to effectively mitigate these problems,
leading to suboptimal context selection. To address this, we propose Selection
using Matrices for Augmented Retrieval (SMART) in question answering tasks, a
fully unsupervised and training-free framework designed to optimize context
selection in RAG. SMART leverages Determinantal Point Processes (DPPs) to
simultaneously model relevance, diversity and conflict, ensuring the selection
of potentially high-quality contexts. Experimental results across multiple
datasets demonstrate that SMART significantly enhances QA performance and
surpasses previous unsupervised context selection methods, showing a promising
strategy for RAG.
