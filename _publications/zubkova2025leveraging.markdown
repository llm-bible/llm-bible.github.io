---
layout: publication
title: 'SUGAR: Leveraging Contextual Confidence For Smarter Retrieval'
authors: Hanna Zubkova, Ji-hoon Park, Seong-whan Lee
conference: "Arxiv"
year: 2025
bibkey: zubkova2025leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.04899"}
tags: ['RAG', 'Applications', 'Reinforcement Learning']
---
Bearing in mind the limited parametric knowledge of Large Language Models
(LLMs), retrieval-augmented generation (RAG) which supplies them with the
relevant external knowledge has served as an approach to mitigate the issue of
hallucinations to a certain extent. However, uniformly retrieving supporting
context makes response generation source-inefficient, as triggering the
retriever is not always necessary, or even inaccurate, when a model gets
distracted by noisy retrieved content and produces an unhelpful answer.
Motivated by these issues, we introduce Semantic Uncertainty Guided Adaptive
Retrieval (SUGAR), where we leverage context-based entropy to actively decide
whether to retrieve and to further determine between single-step and multi-step
retrieval. Our empirical results show that selective retrieval guided by
semantic uncertainty estimation improves the performance across diverse
question answering tasks, as well as achieves a more efficient inference.
