---
layout: publication
title: 'Rezero: Enhancing LLM Search Ability By Trying One-more-time'
authors: Alan Gia Tuan Dao Dao, Thinh Le
conference: "Arxiv"
year: 2025
bibkey: dao2025enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.11001"}
tags: ['Agentic', 'Security', 'Tools', 'Reinforcement Learning', 'RAG']
---
Retrieval-Augmented Generation (RAG) improves Large Language Model (LLM)
performance on knowledge-intensive tasks but depends heavily on initial search
query quality. Current methods, often using Reinforcement Learning (RL),
typically focus on query formulation or reasoning over results, without
explicitly encouraging persistence after a failed search. We introduce ReZero
(Retry-Zero), a novel RL framework that directly rewards the act of retrying a
search query following an initial unsuccessful attempt. This incentivizes the
LLM to explore alternative queries rather than prematurely halting. ReZero
demonstrates significant improvement, achieving 46.88% accuracy compared to a
25% baseline. By rewarding persistence, ReZero enhances LLM robustness in
complex information-seeking scenarios where initial queries may prove
insufficient.
