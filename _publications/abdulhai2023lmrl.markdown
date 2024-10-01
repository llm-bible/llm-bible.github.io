---
layout: publication
title: 'LMRL Gym: Benchmarks For Multi-turn Reinforcement Learning With Language Models'
authors: Abdulhai Marwa, White Isadora, Snell Charlie, Sun Charles, Hong Joey, Zhai Yuexiang, Xu Kelvin, Levine Sergey
conference: "Arxiv"
year: 2023
bibkey: abdulhai2023lmrl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.18232"}
tags: ['Agentic', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
"Large language models (LLMs) provide excellent text-generation capabilities, but standard prompting and generation methods generally do not lead to intentional or goal-directed agents and might necessitate considerable prompt tuning. This becomes particularly apparent in multi-turn conversations: even the best current LLMs rarely ask clarifying questions, engage in explicit information gathering, or take actions now that lead to better decisions after multiple turns. Reinforcement learning has the potential to leverage the powerful modeling capabilities of LLMs, as well as their internal representation of textual interactions, to create capable goal-directed language agents. This can enable intentional and temporally extended interactions, such as with humans, through coordinated persuasion and carefully crafted questions, or in goal-directed play through text games to bring about desired final outcomes. However, enabling this requires the community to develop stable and reliable reinforcement learning algorithms that can effectively train LLMs. Developing such algorithms requires tasks that can gauge progress on algorithm design, provide accessible and reproducible evaluations for multi-turn interactions, and cover a range of task properties and challenges in improving reinforcement learning algorithms. Our paper introduces the LMRL-Gym benchmark for evaluating multi-turn RL for LLMs, together with an open-source research framework containing a basic toolkit for getting started on multi-turn RL with offline value-based and policy-based RL methods. Our benchmark consists of 8 different language tasks, which require multiple rounds of language interaction and cover a range of tasks in open-ended dialogue and text games."
