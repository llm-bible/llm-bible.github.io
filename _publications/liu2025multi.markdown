---
layout: publication
title: 'Hoprag: Multi-hop Reasoning For Logic-aware Retrieval-augmented Generation'
authors: Hao Liu, Zhengren Wang, Xi Chen, Zhiyu Li, Feiyu Xiong, Qinhan Yu, Wentao Zhang
conference: "Arxiv"
year: 2025
bibkey: liu2025multi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12442"}
tags: ['RAG', 'Fine-Tuning', 'Tools']
---
Retrieval-Augmented Generation (RAG) systems often struggle with imperfect retrieval, as traditional retrievers focus on lexical or semantic similarity rather than logical relevance. To address this, we propose \textbf\{HopRAG\}, a novel RAG framework that augments retrieval with logical reasoning through graph-structured knowledge exploration. During indexing, HopRAG constructs a passage graph, with text chunks as vertices and logical connections established via LLM-generated pseudo-queries as edges. During retrieval, it employs a \textit\{retrieve-reason-prune\} mechanism: starting with lexically or semantically similar passages, the system explores multi-hop neighbors guided by pseudo-queries and LLM reasoning to identify truly relevant ones. Experiments on multiple multi-hop benchmarks demonstrate that HopRAG's \textit\{retrieve-reason-prune\} mechanism can expand the retrieval scope based on logical connections and improve final answer quality.
