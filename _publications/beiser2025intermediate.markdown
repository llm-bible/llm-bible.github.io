---
layout: publication
title: 'Intermediate Languages Matter: Formal Choice Drives Neurosymbolic LLM Reasoning'
authors: Alexander Beiser, David Penz, Nysret Musliu
conference: "Arxiv"
year: 2025
bibkey: beiser2025intermediate
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.17216'}
tags: ['RAG']
---
Large language models (LLMs) achieve astonishing results on a wide range of tasks. However, their formal reasoning ability still lags behind. A promising approach is Neurosymbolic LLM reasoning. It works by using LLMs as translators from natural to formal languages and symbolic solvers for deriving correct results. Still, it remains unclear what the contributing factors to the success of Neurosymbolic LLM reasoning are. This paper shows that one important factor is the choice of the formal language. By comparing 4 formal languages on 3 datasets over 6 LLMs, we show that the choice of formal language affects both the syntactic and the semantic reasoning capability. Thereby, we introduce the intermediate language challenge, which is the challenge of picking a suitable formal language for neurosymbolic reasoning. Further, we compare the effects of using different in-context-learning examples in an ablation study. We conclude that on average, context-aware encodings help LLMs to reason, while there is no apparent effect of using comments or markdown syntax.
