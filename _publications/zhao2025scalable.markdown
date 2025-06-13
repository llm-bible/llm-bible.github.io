---
layout: publication
title: 'COLA: A Scalable Multi-agent Framework For Windows UI Task Automation'
authors: Di Zhao, Longhui Ma, Siwei Wang, Miao Wang, Zhao Lv
conference: "Arxiv"
year: 2025
bibkey: zhao2025scalable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.09263'}
  - {name: "Code", url: 'https://github.com/Alokia/COLA-demo'}
tags: ['Agentic', 'Has Code', 'RAG', 'Model Architecture', 'Tools', 'Reinforcement Learning']
---
With the rapid advancements in Large Language Models (LLMs), an increasing
number of studies have leveraged LLMs as the cognitive core of agents to
address complex task decision-making challenges. Specially, recent research has
demonstrated the potential of LLM-based agents on automating Windows GUI
operations. However, existing methodologies exhibit two critical challenges:
(1) static agent architectures fail to dynamically adapt to the heterogeneous
requirements of OS-level tasks, leading to inadequate scenario
generalization;(2) the agent workflows lack fault tolerance mechanism,
necessitating complete process re-execution for UI agent decision error. To
address these limitations, we introduce \textit\{COLA\}, a collaborative
multi-agent framework for automating Windows UI operations. In this framework,
a scenario-aware agent Task Scheduler decomposes task requirements into atomic
capability units, dynamically selects the optimal agent from a decision agent
pool, effectively responds to the capability requirements of diverse scenarios.
The decision agent pool supports plug-and-play expansion for enhanced
flexibility. In addition, we design a memory unit equipped to all agents for
their self-evolution. Furthermore, we develop an interactive backtracking
mechanism that enables human to intervene to trigger state rollbacks for
non-destructive process repair. Our experimental results on the GAIA benchmark
demonstrates that the \textit\{COLA\} framework achieves state-of-the-art
performance with an average score of 31.89%, significantly outperforming
baseline approaches without web API integration. Ablation studies further
validate the individual contributions of our dynamic scheduling. The code is
available at https://github.com/Alokia/COLA-demo.
