---
layout: publication
title: 'Plan*rag: Efficient Test-time Planning For Retrieval Augmented Generation'
authors: Prakhar Verma, Sukruta Prakash Midigeshi, Gaurav Sinha, Arno Solin, Nagarajan Natarajan, Amit Sharma
conference: "Arxiv"
year: 2024
bibkey: verma2024efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.20753'}
tags: ['RAG', 'Fine-Tuning', 'Efficiency and Optimization', 'Tools']
---
We introduce Plan*RAG, a novel framework that enables structured multi-hop
reasoning in retrieval-augmented generation (RAG) through test-time reasoning
plan generation. While existing approaches such as ReAct maintain reasoning
chains within the language model's context window, we observe that this often
leads to plan fragmentation and execution failures. Our key insight is that by
isolating the reasoning plan as a directed acyclic graph (DAG) outside the LM's
working memory, we can enable (1) systematic exploration of reasoning paths,
(2) atomic subqueries enabling precise retrievals and grounding, and (3)
efficiency through parallel execution and bounded context window utilization.
Moreover, Plan*RAG's modular design allows it to be integrated with existing
RAG methods, thus providing a practical solution to improve current RAG
systems. On standard multi-hop reasoning benchmarks, Plan*RAG consistently
achieves improvements over recently proposed methods such as RQ-RAG and
Self-RAG, while maintaining comparable computational costs.
