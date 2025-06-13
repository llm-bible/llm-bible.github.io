---
layout: publication
title: 'Mcts-judge: Test-time Scaling In Llm-as-a-judge For Code Correctness Evaluation'
authors: Yutong Wang, Pengliang Ji, Chaoqun Yang, Kaixin Li, Ming Hu, Jiaoyang Li, Guillaume Sartoretti
conference: "Arxiv"
year: 2025
bibkey: wang2025mcts
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12468"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Scaling Laws', 'Reinforcement Learning', 'RAG', 'Large-Scale Training', 'Pre-Training']
---
The LLM-as-a-Judge paradigm shows promise for evaluating generative content
but lacks reliability in reasoning-intensive scenarios, such as programming.
Inspired by recent advances in reasoning models and shifts in scaling laws, we
pioneer bringing test-time computation into LLM-as-a-Judge, proposing
MCTS-Judge, a resource-efficient, System-2 thinking framework for code
correctness evaluation. MCTS-Judge leverages Monte Carlo Tree Search (MCTS) to
decompose problems into simpler, multi-perspective evaluations. Through a
node-selection strategy that combines self-assessment based on historical
actions in the current trajectory and the Upper Confidence Bound for Trees
based on prior rollouts, MCTS-Judge balances global optimization and refinement
of the current trajectory. We further designed a high-precision,
unit-test-level reward mechanism to encourage the Large Language Model (LLM) to
perform line-by-line analysis. Extensive experiments on three benchmarks and
five LLMs demonstrate the effectiveness of MCTS-Judge, which improves the base
model's accuracy from 41% to 80%, surpassing the o1-series models with 3x fewer
tokens. Further evaluations validate the superiority of its reasoning
trajectory in logic, analytics, thoroughness, and overall quality, while
revealing the test-time scaling law of the LLM-as-a-Judge paradigm.
