---
layout: publication
title: 'Pragmatic Reasoning Improves LLM Code Generation'
authors: Zhuchen Cao, Sven Apel, Adish Singla, Vera Demberg
conference: "Arxiv"
year: 2025
bibkey: cao2025pragmatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.15835"}
tags: ['RAG', 'Applications', 'Tools']
---
Large Language Models (LLMs) have demonstrated impressive potential in
translating natural language (NL) instructions into program code. However, user
instructions often contain inherent ambiguities, making it challenging for LLMs
to generate code that accurately reflects the user's true intent. To address
this challenge, researchers have proposed to produce multiple candidates of the
program code and then rerank them to identify the best solution. In this paper,
we propose CodeRSA, a novel code candidate reranking mechanism built upon the
Rational Speech Act (RSA) framework, designed to guide LLMs toward more
comprehensive pragmatic reasoning about user intent. We evaluate CodeRSA using
one of the latest LLMs on a popular code generation dataset. Our experiment
results show that CodeRSA consistently outperforms common baselines, surpasses
the state-of-the-art approach in most cases, and demonstrates robust overall
performance. These findings underscore the effectiveness of integrating
pragmatic reasoning into code candidate reranking, offering a promising
direction for enhancing code generation quality in LLMs.
