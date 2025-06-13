---
layout: publication
title: 'Hyper-rag: Combating LLM Hallucinations Using Hypergraph-driven Retrieval-augmented Generation'
authors: Yifan Feng, Hao Hu, Xingliang Hou, Shiquan Liu, Shihui Ying, Shaoyi Du, Han Hu, Yue Gao
conference: "Arxiv"
year: 2025
bibkey: feng2025hyper
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08758'}
tags: ['RAG', 'Applications']
---
Large language models (LLMs) have transformed various sectors, including
education, finance, and medicine, by enhancing content generation and
decision-making processes. However, their integration into the medical field is
cautious due to hallucinations, instances where generated content deviates from
factual accuracy, potentially leading to adverse outcomes. To address this, we
introduce Hyper-RAG, a hypergraph-driven Retrieval-Augmented Generation method
that comprehensively captures both pairwise and beyond-pairwise correlations in
domain-specific knowledge, thereby mitigating hallucinations. Experiments on
the NeurologyCrop dataset with six prominent LLMs demonstrated that Hyper-RAG
improves accuracy by an average of 12.3% over direct LLM use and outperforms
Graph RAG and Light RAG by 6.3% and 6.0%, respectively. Additionally, Hyper-RAG
maintained stable performance with increasing query complexity, unlike existing
methods which declined. Further validation across nine diverse datasets showed
a 35.5% performance improvement over Light RAG using a selection-based
assessment. The lightweight variant, Hyper-RAG-Lite, achieved twice the
retrieval speed and a 3.3% performance boost compared with Light RAG. These
results confirm Hyper-RAG's effectiveness in enhancing LLM reliability and
reducing hallucinations, making it a robust solution for high-stakes
applications like medical diagnostics.
