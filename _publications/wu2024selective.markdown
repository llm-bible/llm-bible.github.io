---
layout: publication
title: 'Repoformer: Selective Retrieval For Repository-level Code Completion'
authors: Di Wu, Wasi Uddin Ahmad, Dejiao Zhang, Murali Krishna Ramanathan, Xiaofei Ma
conference: "Arxiv"
year: 2024
bibkey: wu2024selective
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.10059"}
tags: ['Tools', 'Efficiency and Optimization', 'RAG', 'Security', 'Training Techniques', 'Pretraining Methods']
---
Recent advances in retrieval-augmented generation (RAG) have initiated a new
era in repository-level code completion. However, the invariable use of
retrieval in existing methods exposes issues in both efficiency and robustness,
with a large proportion of the retrieved contexts proving unhelpful or harmful
to code language models (code LMs). In this paper, we propose a selective RAG
framework to avoid retrieval when unnecessary. To power this framework, we
design a self-supervised learning approach to enable a code LM to accurately
self-evaluate whether retrieval can improve its output quality and robustly
leverage the potentially noisy retrieved contexts. Using this LM as both the
selective RAG policy and the generation model, our framework achieves
state-of-the-art repository-level code completion performance on diverse
benchmarks including RepoEval, CrossCodeEval, and CrossCodeLongEval, a new
long-form code completion benchmark. Meanwhile, our analyses show that
selectively retrieving brings as much as 70% inference speedup in the online
serving setting without harming the performance. We further demonstrate that
our framework is able to accommodate different generation models, retrievers,
and programming languages. These advancements position our framework as an
important step towards more accurate and efficient repository-level code
completion.
