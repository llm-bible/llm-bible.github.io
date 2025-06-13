---
layout: publication
title: 'Large Language Model Meets Constraint Propagation'
authors: Alexandre Bonlarron, Florian Régin, Elisabetta De Maria, Jean-charles Régin
conference: "Arxiv"
year: 2025
bibkey: bonlarron2025large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.24012'}
tags: ['Masked Language Model', 'Language Modeling', 'RAG', 'BERT', 'Applications', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) excel at generating fluent text but struggle to enforce external constraints because they generate tokens sequentially without explicit control mechanisms. GenCP addresses this limitation by combining LLM predictions with Constraint Programming (CP) reasoning, formulating text generation as a Constraint Satisfaction Problem (CSP). In this paper, we improve GenCP by integrating Masked Language Models (MLMs) for domain generation, which allows bidirectional constraint propagation that leverages both past and future tokens. This integration bridges the gap between token-level prediction and structured constraint enforcement, leading to more reliable and constraint-aware text generation. Our evaluation on COLLIE benchmarks demonstrates that incorporating domain preview via MLM calls significantly improves GenCP's performance. Although this approach incurs additional MLM calls and, in some cases, increased backtracking, the overall effect is a more efficient use of LLM inferences and an enhanced ability to generate feasible and meaningful solutions, particularly in tasks with strict content constraints.
