---
layout: publication
title: 'To Backtrack Or Not To Backtrack: When Sequential Search Limits Model Reasoning'
authors: Tian Qin, David Alvarez-melis, Samy Jelassi, Eran Malach
conference: "Arxiv"
year: 2025
bibkey: qin2025backtrack
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07052"}
tags: ['Training Techniques', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Recent advancements in large language models have significantly improved
their reasoning abilities, particularly through techniques involving search and
backtracking. Backtracking naturally scales test-time compute by enabling
sequential, linearized exploration via long chain-of-thought (CoT) generation.
However, this is not the only strategy for scaling test-time compute: parallel
sampling with best-of-n selection provides an alternative that generates
diverse solutions simultaneously. Despite the growing adoption of sequential
search, its advantages over parallel sampling--especially under a fixed compute
budget remain poorly understood. In this paper, we systematically compare these
two approaches on two challenging reasoning tasks: CountDown and Sudoku.
Surprisingly, we find that sequential search underperforms parallel sampling on
CountDown but outperforms it on Sudoku, suggesting that backtracking is not
universally beneficial. We identify two factors that can cause backtracking to
degrade performance: (1) training on fixed search traces can lock models into
suboptimal strategies, and (2) explicit CoT supervision can discourage
"implicit" (non-verbalized) reasoning. Extending our analysis to reinforcement
learning (RL), we show that models with backtracking capabilities benefit
significantly from RL fine-tuning, while models without backtracking see
limited, mixed gains. Together, these findings challenge the assumption that
backtracking universally enhances LLM reasoning, instead revealing a complex
interaction between task structure, training data, model scale, and learning
paradigm.
