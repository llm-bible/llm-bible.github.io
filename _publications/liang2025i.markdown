---
layout: publication
title: 'I-MCTS: Enhancing Agentic Automl Via Introspective Monte Carlo Tree Search'
authors: Zujie Liang, Feng Wei, Wujiang Xu, Lin Chen, Yuxi Qian, Xinhui Wu
conference: "Arxiv"
year: 2025
bibkey: liang2025i
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14693'}
  - {name: "Code", url: 'https://github.com/jokieleung/I-MCTS'}
tags: ['Reinforcement Learning', 'Agentic', 'Has Code', 'Applications']
---
Recent advancements in large language models (LLMs) have shown remarkable
potential in automating machine learning tasks. However, existing LLM-based
agents often struggle with low-diversity and suboptimal code generation. While
recent work has introduced Monte Carlo Tree Search (MCTS) to address these
issues, limitations persist in the quality and diversity of thoughts generated,
as well as in the scalar value feedback mechanisms used for node selection. In
this study, we introduce Introspective Monte Carlo Tree Search (I-MCTS), a
novel approach that iteratively expands tree nodes through an introspective
process that meticulously analyzes solutions and results from parent and
sibling nodes. This facilitates a continuous refinement of the node in the
search tree, thereby enhancing the overall decision-making process.
Furthermore, we integrate a Large Language Model (LLM)-based value model to
facilitate direct evaluation of each node's solution prior to conducting
comprehensive computational rollouts. A hybrid rewarding mechanism is
implemented to seamlessly transition the Q-value from LLM-estimated scores to
actual performance scores. This allows higher-quality nodes to be traversed
earlier. Applied to the various ML tasks, our approach demonstrates a 6%
absolute improvement in performance compared to the strong open-source AutoML
agents, showcasing its effectiveness in enhancing agentic AutoML systems.
Resource available at https://github.com/jokieleung/I-MCTS
