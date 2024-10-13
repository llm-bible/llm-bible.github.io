---
layout: publication
title: 'Hierarchical Continual Reinforcement Learning Via Large Language Model'
authors: Pan Chaofan, Yang Xin, Wang Hao, Wei Wei, Li Tianrui
conference: "Arxiv"
year: 2024
bibkey: pan2024hierarchical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.15098"}
tags: ['Agentic', 'Reinforcement Learning', 'Tools']
---
The ability to learn continuously in dynamic environments is a crucial
requirement for reinforcement learning (RL) agents applying in the real world.
Despite the progress in continual reinforcement learning (CRL), existing
methods often suffer from insufficient knowledge transfer, particularly when
the tasks are diverse. To address this challenge, we propose a new framework,
Hierarchical Continual reinforcement learning via large language model
(Hi-Core), designed to facilitate the transfer of high-level knowledge. Hi-Core
orchestrates a twolayer structure: high-level policy formulation by a large
language model (LLM), which represents agenerates a sequence of goals, and
low-level policy learning that closely aligns with goal-oriented RL practices,
producing the agent's actions in response to the goals set forth. The framework
employs feedback to iteratively adjust and verify highlevel policies, storing
them along with low-level policies within a skill library. When encountering a
new task, Hi-Core retrieves relevant experience from this library to help to
learning. Through experiments on Minigrid, Hi-Core has demonstrated its
effectiveness in handling diverse CRL tasks, which outperforms popular
baselines.
