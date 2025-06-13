---
layout: publication
title: 'THOUGHTSCULPT: Reasoning With Intermediate Revision And Search'
authors: Yizhou Chi, Kevin Yang, Dan Klein
conference: "Arxiv"
year: 2024
bibkey: chi2024reasoning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.05966'}
tags: ['Reinforcement Learning', 'RAG']
---
We present THOUGHTSCULPT, a general reasoning and search method for tasks
with outputs that can be decomposed into components. THOUGHTSCULPT explores a
search tree of potential solutions using Monte Carlo Tree Search (MCTS),
building solutions one action at a time and evaluating according to any
domain-specific heuristic, which in practice is often simply an LLM evaluator.
Critically, our action space includes revision actions: THOUGHTSCULPT may
choose to revise part of its previous output rather than continuing to build
the rest of its output. Empirically, THOUGHTSCULPT outperforms state-of-the-art
reasoning methods across three challenging tasks: Story Outline Improvement (up
to +30% interestingness), Mini-Crosswords Solving (up to +16% word success
rate), and Constrained Generation (up to +10% concept coverage).
