---
layout: publication
title: 'Corag: Collaborative Retrieval-augmented Generation'
authors: Aashiq Muhamed, Mona Diab, Virginia Smith
conference: "Arxiv"
year: 2025
bibkey: muhamed2025collaborative
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.01883'}
tags: ['Few-Shot', 'RAG', 'Tools']
---
Retrieval-Augmented Generation (RAG) models excel in knowledge-intensive
tasks, especially under few-shot learning constraints. We introduce CoRAG, a
framework extending RAG to collaborative settings, where clients jointly train
a shared model using a collaborative passage store. To evaluate CoRAG, we
introduce CRAB, a benchmark for collaborative homogeneous open-domain question
answering. Our experiments demonstrate that CoRAG consistently outperforms both
parametric collaborative learning methods and locally trained RAG models in
low-resource scenarios. Further analysis reveals the critical importance of
relevant passages within the shared store, the surprising benefits of
incorporating irrelevant passages, and the potential for hard negatives to
negatively impact performance. This introduces a novel consideration in
collaborative RAG: the trade-off between leveraging a collectively enriched
knowledge base and the potential risk of incorporating detrimental passages
from other clients. Our findings underscore the viability of CoRAG, while also
highlighting key design challenges and promising avenues for future research.
