---
layout: publication
title: 'DRAGIN: Dynamic Retrieval Augmented Generation Based On The Information Needs Of Large Language Models'
authors: Weihang Su, Yichen Tang, Qingyao Ai, Zhijing Wu, Yiqun Liu
conference: "Arxiv"
year: 2024
bibkey: su2024dynamic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.10081'}
  - {name: "Code", url: 'https://github.com/oneal2000/DRAGIN/tree/main'}
tags: ['Has Code', 'Language Modeling', 'RAG', 'Applications', 'Tools']
---
Dynamic retrieval augmented generation (RAG) paradigm actively decides when
and what to retrieve during the text generation process of Large Language
Models (LLMs). There are two key elements of this paradigm: identifying the
optimal moment to activate the retrieval module (deciding when to retrieve) and
crafting the appropriate query once retrieval is triggered (determining what to
retrieve). However, current dynamic RAG methods fall short in both aspects.
Firstly, the strategies for deciding when to retrieve often rely on static
rules. Moreover, the strategies for deciding what to retrieve typically limit
themselves to the LLM's most recent sentence or the last few tokens, while the
LLM's real-time information needs may span across the entire context. To
overcome these limitations, we introduce a new framework, DRAGIN, i.e., Dynamic
Retrieval Augmented Generation based on the real-time Information Needs of
LLMs. Our framework is specifically designed to make decisions on when and what
to retrieve based on the LLM's real-time information needs during the text
generation process. We evaluate DRAGIN along with existing methods
comprehensively over 4 knowledge-intensive generation datasets. Experimental
results show that DRAGIN achieves superior performance on all tasks,
demonstrating the effectiveness of our method. We have open-sourced all the
code, data, and models in GitHub: https://github.com/oneal2000/DRAGIN/tree/main
