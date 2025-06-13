---
layout: publication
title: 'Model Cascading For Code: A Cascaded Black-box Multi-model Framework For Cost-efficient Code Completion With Self-testing'
authors: Boyuan Chen, Mingzhi Zhu, Brendan Dolan-gavitt, Muhammad Shafique, Siddharth Garg
conference: "Arxiv"
year: 2024
bibkey: chen2024model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15842"}
tags: ['RAG', 'Tools', 'Applications', 'Reinforcement Learning']
---
The rapid advancement of large language models (LLMs) has significantly
improved code completion tasks, yet the trade-off between accuracy and
computational cost remains a critical challenge. While using larger models and
incorporating inference-time self-testing algorithms can significantly improve
output accuracy, they incur substantial computational expenses at the same
time. Furthermore, servers in real-world scenarios usually have a dynamic
preference on the cost-accuracy tradeoff, depending on the budget, bandwidth,
the concurrent user volume, and users' sensitivity to wrong answers. In this
work, we introduce a novel framework combining model cascading and
inference-time self-feedback algorithms to find multiple near-optimal
self-testing options on the cost-accuracy tradeoff in LLM-based code
generation. Our approach leverages self-generated tests to both enhance
accuracy and evaluate model cascading decisions. As a blackbox inference-time
method, it requires no access to internal model parameters. We further propose
a threshold-based algorithm to determine when to deploy larger models and a
heuristic to optimize the number of solutions, test cases, and test lines
generated per model, based on budget constraints. Experimental results show
that our cascading approach reduces costs by an average of 26%, and up to 70%
in the best case, across various model families and datasets, while maintaining
or improving accuracy in natural language generation tasks compared to both
random and optimal single-model self-testing schemes. To our knowledge, this is
the first work to provide a series of choices for optimizing the cost-accuracy
trade-off in LLM code generation with self-testing.
