---
layout: publication
title: 'ARAGOG: Advanced RAG Output Grading'
authors: Matouš Eibich, Shivay Nagpal, Alexander Fred-ojala
conference: "Arxiv"
year: 2024
bibkey: eibich2024advanced
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.01037'}
  - {name: "Code", url: 'https://github.com/predlico/ARAGOG)'}
tags: ['RAG', 'Fine-Tuning', 'Has Code']
---
Retrieval-Augmented Generation (RAG) is essential for integrating external
knowledge into Large Language Model (LLM) outputs. While the literature on RAG
is growing, it primarily focuses on systematic reviews and comparisons of new
state-of-the-art (SoTA) techniques against their predecessors, with a gap in
extensive experimental comparisons. This study begins to address this gap by
assessing various RAG methods' impacts on retrieval precision and answer
similarity. We found that Hypothetical Document Embedding (HyDE) and LLM
reranking significantly enhance retrieval precision. However, Maximal Marginal
Relevance (MMR) and Cohere rerank did not exhibit notable advantages over a
baseline Naive RAG system, and Multi-query approaches underperformed. Sentence
Window Retrieval emerged as the most effective for retrieval precision, despite
its variable performance on answer similarity. The study confirms the potential
of the Document Summary Index as a competent retrieval approach. All resources
related to this research are publicly accessible for further investigation
through our GitHub repository ARAGOG (https://github.com/predlico/ARAGOG). We
welcome the community to further this exploratory study in RAG systems.
