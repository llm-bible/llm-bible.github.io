---
layout: publication
title: 'Rallrec: Improving Retrieval Augmented Large Language Model Recommendation With Representation Learning'
authors: Jian Xu, Sichun Luo, Xiangyu Chen, Haoming Huang, Hanxu Hou, Linqi Song
conference: "Arxiv"
year: 2025
bibkey: xu2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06101"}
  - {name: "Code", url: "https://github.com/JianXu95/RALLRec"}
tags: ['RAG', 'Reinforcement Learning', 'LREC', 'Has Code', 'Prompting']
---
Large Language Models (LLMs) have been integrated into recommendation systems
to enhance user behavior comprehension. The Retrieval Augmented Generation
(RAG) technique is further incorporated into these systems to retrieve more
relevant items and improve system performance. However, existing RAG methods
rely primarily on textual semantics and often fail to incorporate the most
relevant items, limiting the effectiveness of the systems.
  In this paper, we propose Representation learning for retrieval-Augmented
Large Language model Recommendation (RALLRec). Specifically, we enhance textual
semantics by prompting LLMs to generate more detailed item descriptions,
followed by joint representation learning of textual and collaborative
semantics, which are extracted by the LLM and recommendation models,
respectively. Considering the potential time-varying characteristics of user
interest, a simple yet effective reranking method is further introduced to
capture the dynamics of user preference. We conducted extensive experiments on
three real-world datasets, and the evaluation results validated the
effectiveness of our method. Code is made public at
https://github.com/JianXu95/RALLRec.
