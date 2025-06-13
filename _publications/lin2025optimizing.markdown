---
layout: publication
title: 'Optimizing Multi-hop Document Retrieval Through Intermediate Representations'
authors: Jiaen Lin, Jingyu Liu, Yingbo Liu
conference: "Arxiv"
year: 2025
bibkey: lin2025optimizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.04796"}
  - {name: "Code", url: "https://anonymous.4open.science/r/L-RAG-ADD5/"}
tags: ['RAG', 'Has Code', 'Reinforcement Learning']
---
Retrieval-augmented generation (RAG) encounters challenges when addressing complex queries, particularly multi-hop questions. While several methods tackle multi-hop queries by iteratively generating internal queries and retrieving external documents, these approaches are computationally expensive. In this paper, we identify a three-stage information processing pattern in LLMs during layer-by-layer reasoning, consisting of extraction, processing, and subsequent extraction steps. This observation suggests that the representations in intermediate layers contain richer information compared to those in other layers. Building on this insight, we propose Layer-wise RAG (L-RAG). Unlike prior methods that focus on generating new internal queries, L-RAG leverages intermediate representations from the middle layers, which capture next-hop information, to retrieve external knowledge. L-RAG achieves performance comparable to multi-step approaches while maintaining inference overhead similar to that of standard RAG. Experimental results show that L-RAG outperforms existing RAG methods on open-domain multi-hop question-answering datasets, including MuSiQue, HotpotQA, and 2WikiMultiHopQA. The code is available in https://anonymous.4open.science/r/L-RAG-ADD5/
