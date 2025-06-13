---
layout: publication
title: 'Syncmind: Measuring Agent Out-of-sync Recovery In Collaborative Software Engineering'
authors: Xuehang Guo, Xingyao Wang, Yangyi Chen, Sha Li, Chi Han, Manling Li, Heng Ji
conference: "Arxiv"
year: 2025
bibkey: guo2025measuring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.06994"}
  - {name: "Code", url: "https://xhguo7.github.io/SyncMind/"}
tags: ['Agentic', 'Has Code', 'Tools', 'Reinforcement Learning']
---
Software engineering (SE) is increasingly collaborative, with developers
working together on shared complex codebases. Effective collaboration in shared
environments requires participants -- whether humans or AI agents -- to stay on
the same page as their environment evolves. When a collaborator's understanding
diverges from the current state -- what we term the out-of-sync challenge --
the collaborator's actions may fail, leading to integration issues. In this
work, we introduce SyncMind, a framework that systematically defines the
out-of-sync problem faced by large language model (LLM) agents in collaborative
software engineering (CSE). Based on SyncMind, we create SyncBench, a benchmark
featuring 24,332 instances of agent out-of-sync scenarios in real-world CSE
derived from 21 popular GitHub repositories with executable verification tests.
Experiments on SyncBench uncover critical insights into existing LLM agents'
capabilities and limitations. Besides substantial performance gaps among agents
(from Llama-3.1 agent <= 3.33% to Claude-3.5-Sonnet >= 28.18%), their
consistently low collaboration willingness (<= 4.86%) suggests fundamental
limitations of existing LLM in CSE. However, when collaboration occurs, it
positively correlates with out-of-sync recovery success. Minimal performance
differences in agents' resource-aware out-of-sync recoveries further reveal
their significant lack of resource awareness and adaptability, shedding light
on future resource-efficient collaborative systems. Code and data are openly
available on our project website: https://xhguo7.github.io/SyncMind/.
