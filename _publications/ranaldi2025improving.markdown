---
layout: publication
title: 'Improving Multilingual Retrieval-augmented Language Models Through Dialectic Reasoning Argumentations'
authors: Leonardo Ranaldi, Federico Ranaldi, Fabio Massimo Zanzotto, Barry Haddow, Alexandra Birch
conference: "Arxiv"
year: 2025
bibkey: ranaldi2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.04771"}
tags: ['Tools', 'Interpretability and Explainability', 'RAG', 'Reinforcement Learning', 'Security']
---
Retrieval-augmented generation (RAG) is key to enhancing large language
models (LLMs) to systematically access richer factual knowledge. Yet, using RAG
brings intrinsic challenges, as LLMs must deal with potentially conflicting
knowledge, especially in multilingual retrieval, where the heterogeneity of
knowledge retrieved may deliver different outlooks. To make RAG more
analytical, critical and grounded, we introduce Dialectic-RAG (DRAG), a modular
approach guided by Argumentative Explanations, i.e., structured reasoning
process that systematically evaluates retrieved
  information by comparing, contrasting, and resolving conflicting
perspectives. Given a query and a set of multilingual related documents, DRAG
selects and exemplifies relevant knowledge for delivering dialectic
explanations that, by critically weighing opposing arguments and filtering
extraneous content, clearly determine the final response. Through a series of
in-depth experiments, we show the impact of our framework both as an in-context
learning strategy and for constructing demonstrations to instruct smaller
models. The final results demonstrate that DRAG significantly improves RAG
approaches, requiring low-impact computational effort and providing robustness
to knowledge perturbations.
