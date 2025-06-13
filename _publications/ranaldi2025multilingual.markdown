---
layout: publication
title: 'Multilingual Retrieval-augmented Generation For Knowledge-intensive Task'
authors: Leonardo Ranaldi, Barry Haddow, Alexandra Birch
conference: "Arxiv"
year: 2025
bibkey: ranaldi2025multilingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.03616"}
tags: ['RAG', 'Efficiency and Optimization']
---
Retrieval-augmented generation (RAG) has become a cornerstone of contemporary
NLP, enhancing large language models (LLMs) by allowing them to access richer
factual contexts through in-context retrieval. While effective in monolingual
settings, especially in English, its use in multilingual tasks remains
unexplored. This paper investigates the effectiveness of RAG across multiple
languages by proposing novel approaches for multilingual open-domain
question-answering. We evaluate the performance of various multilingual RAG
strategies, including question-translation (tRAG), which translates questions
into English before retrieval, and Multilingual RAG (MultiRAG), where retrieval
occurs directly across multiple languages. Our findings reveal that tRAG, while
useful, suffers from limited coverage. In contrast, MultiRAG improves
efficiency by enabling multilingual retrieval but introduces inconsistencies
due to cross-lingual variations in the retrieved content. To address these
issues, we propose Crosslingual RAG (CrossRAG), a method that translates
retrieved documents into a common language (e.g., English) before generating
the response. Our experiments show that CrossRAG significantly enhances
performance on knowledge-intensive tasks, benefiting both high-resource and
low-resource languages.
