---
layout: publication
title: 'Boosting Universal LLM Reward Design Through Heuristic Reward Observation Space Evolution'
authors: Zen Kit Heng, Zimeng Zhao, Tianhao Wu, Yuanfei Wang, Mingdong Wu, Yangang Wang, Hao Dong
conference: "Arxiv"
year: 2025
bibkey: heng2025boosting
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.07596'}
tags: ['Agentic', 'RAG', 'Applications', 'Merging', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning']
---
Large Language Models (LLMs) are emerging as promising tools for automated
reinforcement learning (RL) reward design, owing to their robust capabilities
in commonsense reasoning and code generation. By engaging in dialogues with RL
agents, LLMs construct a Reward Observation Space (ROS) by selecting relevant
environment states and defining their internal operations. However, existing
frameworks have not effectively leveraged historical exploration data or manual
task descriptions to iteratively evolve this space. In this paper, we propose a
novel heuristic framework that enhances LLM-driven reward design by evolving
the ROS through a table-based exploration caching mechanism and a text-code
reconciliation strategy. Our framework introduces a state execution table,
which tracks the historical usage and success rates of environment states,
overcoming the Markovian constraint typically found in LLM dialogues and
facilitating more effective exploration. Furthermore, we reconcile
user-provided task descriptions with expert-defined success criteria using
structured prompts, ensuring alignment in reward design objectives.
Comprehensive evaluations on benchmark RL tasks demonstrate the effectiveness
and stability of the proposed framework. Code and video demos are available at
jingjjjjjie.github.io/LLM2Reward.
