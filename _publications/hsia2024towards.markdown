---
layout: publication
title: 'RAGGED: Towards Informed Design Of Retrieval Augmented Generation Systems'
authors: Jennifer Hsia, Afreen Shaikh, Zhiruo Wang, Graham Neubig
conference: "Arxiv"
year: 2024
bibkey: hsia2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.09040"}
tags: ['RAG', 'Tools', 'Applications']
---
Retrieval-augmented generation (RAG) can significantly improve the
performance of language models (LMs) by providing additional context for tasks
such as document-based question answering (DBQA). However, the effectiveness of
RAG is highly dependent on its configuration. To systematically find the
optimal configuration, we introduce RAGGED, a framework for analyzing RAG
configurations across various DBQA tasks. Using the framework, we discover
distinct LM behaviors in response to varying context quantities, context
qualities, and retrievers. For instance, while some models are robust to noisy
contexts, monotonically performing better with more contexts, others are more
noise-sensitive and can effectively use only a few contexts before declining in
performance. This framework also provides a deeper analysis of these
differences by evaluating the LMs' sensitivity to signal and noise under
specific context quality conditions. Using RAGGED, researchers and
practitioners can derive actionable insights about how to optimally configure
their RAG systems for their specific question-answering tasks.
