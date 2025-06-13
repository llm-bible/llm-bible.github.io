---
layout: publication
title: 'Stateact: Enhancing LLM Base Agents Via Self-prompting And State-tracking'
authors: Nikolai Rozanov, Marek Rei
conference: "Arxiv"
year: 2024
bibkey: rozanov2024enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.02810'}
  - {name: "Code", url: 'https://github.com/ai-nikolai/stateact'}
tags: ['Agentic', 'Has Code', 'Agent', 'Efficiency and Optimization', 'Training Techniques', 'Prompting', 'Reinforcement Learning']
---
Large language models (LLMs) are increasingly used as autonomous agents,
tackling tasks from robotics to web navigation. Their performance depends on
the underlying base agent. Existing methods, however, struggle with
long-context reasoning and goal adherence. We introduce StateAct, a novel and
efficient base agent that enhances decision-making through (1) self-prompting,
which reinforces task goals at every step, and (2) chain-of-states, an
extension of chain-of-thought that tracks state information over time. StateAct
outperforms ReAct, the previous best base agent, by over 10% on Alfworld, 30%
on Textcraft, and 7% on Webshop across multiple frontier LLMs. We also
demonstrate that StateAct can be used as a drop-in replacement for ReAct with
advanced LLM agent methods such as test-time scaling, yielding an additional
12% gain on Textcraft. By improving efficiency and long-range reasoning without
requiring additional training or retrieval, StateAct provides a scalable
foundation for LLM agents. We open source our code to support further research
at https://github.com/ai-nikolai/stateact .
