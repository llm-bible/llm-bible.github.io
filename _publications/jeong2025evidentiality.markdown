---
layout: publication
title: 'Ecorag: Evidentiality-guided Compression For Long Context RAG'
authors: Yeonseok Jeong, Jinsu Kim, Dohyeon Lee, Seung-won Hwang
conference: "Arxiv"
year: 2025
bibkey: jeong2025evidentiality
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.05167'}
  - {name: "Code", url: 'https://github.com/ldilab/ECoRAG'}
tags: ['Has Code', 'RAG', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large Language Models (LLMs) have shown remarkable performance in Open-Domain Question Answering (ODQA) by leveraging external documents through Retrieval-Augmented Generation (RAG). To reduce RAG overhead, from longer context, context compression is necessary. However, prior compression methods do not focus on filtering out non-evidential information, which limit the performance in LLM-based RAG. We thus propose Evidentiality-guided RAG, or \textbf\{ECoRAG\} framework. ECoRAG improves LLM performance by compressing retrieved documents based on evidentiality, ensuring whether answer generation is supported by the correct evidence. As an additional step, ECoRAG reflects whether the compressed content provides sufficient evidence, and if not, retrieves more until sufficient. Experiments show that ECoRAG improves LLM performance on ODQA tasks, outperforming existing compression methods. Furthermore, ECoRAG is highly cost-efficient, as it not only reduces latency but also minimizes token usage by retaining only the necessary information to generate the correct answer. Code is available at https://github.com/ldilab/ECoRAG.
