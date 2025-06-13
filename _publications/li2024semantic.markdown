---
layout: publication
title: 'Semantic Convergence: Harmonizing Recommender Systems Via Two-stage Alignment And Behavioral Semantic Tokenization'
authors: Guanghan Li, Xun Zhang, Yufei Zhang, Yifan Yin, Guojun Yin, Wei Lin
conference: "Arxiv"
year: 2024
bibkey: li2024semantic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.13771'}
tags: ['RecSys', 'Tokenization', 'Tools']
---
Large language models (LLMs), endowed with exceptional reasoning
capabilities, are adept at discerning profound user interests from historical
behaviors, thereby presenting a promising avenue for the advancement of
recommendation systems. However, a notable discrepancy persists between the
sparse collaborative semantics typically found in recommendation systems and
the dense token representations within LLMs. In our study, we propose a novel
framework that harmoniously merges traditional recommendation models with the
prowess of LLMs. We initiate this integration by transforming ItemIDs into
sequences that align semantically with the LLMs space, through the proposed
Alignment Tokenization module. Additionally, we design a series of specialized
supervised learning tasks aimed at aligning collaborative signals with the
subtleties of natural language semantics. To ensure practical applicability, we
optimize online inference by pre-caching the top-K results for each user,
reducing latency and improving effciency. Extensive experimental evidence
indicates that our model markedly improves recall metrics and displays
remarkable scalability of recommendation systems.
