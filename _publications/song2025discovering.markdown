---
layout: publication
title: 'Discovering Knowledge Deficiencies Of Language Models On Massive Knowledge Base'
authors: Linxin Song, Xuwei Ding, Jieyu Zhang, Taiwei Shi, Ryotaro Shimizu, Rahul Gupta, Yang Liu, Jian Kang, Jieyu Zhao
conference: "Arxiv"
year: 2025
bibkey: song2025discovering
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.23361'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Pretraining Methods']
---
Large language models (LLMs) possess impressive linguistic capabilities but
often fail to faithfully retain factual knowledge, leading to hallucinations
and unreliable outputs. Understanding LLMs' knowledge deficiencies by
exhaustively evaluating against full-scale knowledge bases is computationally
prohibitive, especially for closed-weight models. We propose stochastic error
ascent (SEA), a scalable and efficient framework for discovering knowledge
deficiencies (errors) in closed-weight LLMs under a strict query budget. Rather
than naively probing all knowledge candidates, SEA formulates error discovery
as a stochastic optimization process: it iteratively retrieves new high-error
candidates by leveraging the semantic similarity to previously observed
failures. To further enhance search efficiency and coverage, SEA employs
hierarchical retrieval across document and paragraph levels, and constructs a
relation directed acyclic graph to model error propagation and identify
systematic failure modes. Empirically, SEA uncovers 40.7x more knowledge errors
than Automated Capability Discovery and 26.7% more than AutoBencher, while
reducing the cost-per-error by 599x and 9x, respectively. Human evaluation
confirms the high quality of generated questions, while ablation and
convergence analyses validate the contribution of each component in SEA.
Further analysis on the discovered errors reveals correlated failure patterns
across LLM families and recurring deficits, highlighting the need for better
data coverage and targeted fine-tuning in future LLM development.
