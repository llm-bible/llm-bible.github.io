---
layout: publication
title: 'Zero-shot And Efficient Clarification Need Prediction In Conversational Search'
authors: Lili Lu, Chuan Meng, Federico Ravenda, Mohammad Aliannejadi, Fabio Crestani
conference: "Arxiv"
year: 2025
bibkey: lu2025zero
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.00179'}
tags: ['Few-Shot', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Prompting']
---
Clarification need prediction (CNP) is a key task in conversational search,
aiming to predict whether to ask a clarifying question or give an answer to the
current user query. However, current research on CNP suffers from the issues of
limited CNP training data and low efficiency. In this paper, we propose a
zero-shot and efficient CNP framework (Zef-CNP), in which we first prompt large
language models (LLMs) in a zero-shot manner to generate two sets of synthetic
queries: ambiguous and specific (unambiguous) queries. We then use the
generated queries to train efficient CNP models. Zef-CNP eliminates the need
for human-annotated clarification-need labels during training and avoids the
use of LLMs with high query latency at query time. To further improve the
generation quality of synthetic queries, we devise a topic-, information-need-,
and query-aware chain-of-thought (CoT) prompting strategy (TIQ-CoT). Moreover,
we enhance TIQ-CoT with counterfactual query generation (CoQu), which guides
LLMs first to generate a specific/ambiguous query and then sequentially
generate its corresponding ambiguous/specific query. Experimental results show
that Zef-CNP achieves superior CNP effectiveness and efficiency compared with
zero- and few-shot LLM-based CNP predictors.
