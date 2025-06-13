---
layout: publication
title: 'Structure-aware Fill-in-the-middle Pretraining For Code'
authors: Linyuan Gong, Alvin Cheung, Mostafa Elhoushi, Sida Wang
conference: "Arxiv"
year: 2025
bibkey: gong2025structure
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00204'}
  - {name: "Code", url: 'https://github.com/gonglinyuan/ast_fim'}
tags: ['Has Code', 'RAG', 'Training Techniques', 'Reinforcement Learning', 'Pretraining Methods']
---
Fill-in-the-Middle (FIM) is a common pretraining method for code LLMs, where models complete code segments given surrounding context. However, existing LLMs treat code as plain text and mask random character spans. We propose and evaluate AST-FIM, a pretraining strategy that leverages Abstract Syntax Trees (ASTs) to mask complete syntactic structures at scale, ensuring coherent training examples better aligned with universal code structures and common code editing patterns such as blocks, expressions, or functions. To evaluate real-world fill-in-the-middle (FIM) programming tasks, we introduce Real-FIM-Eval, a benchmark derived from 30,000+ GitHub commits across 12 languages. On infilling tasks, experiments on 1B and 8B parameter models show that AST-FIM is particularly beneficial for real-world code editing as it outperforms standard random-character FIM by up to 5 pts on standard FIM benchmarks. Our code is publicly available at https://github.com/gonglinyuan/ast_fim.
