---
layout: publication
title: 'MOSS: Enabling Code-driven Evolution And Context Management For AI Agents'
authors: Ming Zhu, Yi Zhou
conference: "Arxiv"
year: 2024
bibkey: zhu2024enabling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.16120'}
tags: ['Agentic', 'Efficiency and Optimization', 'Applications', 'Tools', 'Prompting']
---
Developing AI agents powered by large language models (LLMs) faces
significant challenges in achieving true Turing completeness and adaptive,
code-driven evolution. Current approaches often generate code independently of
its runtime context, relying heavily on the LLM's memory, which results in
inefficiencies and limits adaptability. Manual protocol development in sandbox
environments further constrains the agent's autonomous adaptability. Crucially,
achieving consistency in code and context across multi-turn interactions and
ensuring isolation of local variables within each interaction remains an
unsolved problem.
  We introduce MOSS (llM-oriented Operating System Simulation), a novel
framework that addresses these challenges by integrating code generation with a
dynamic context management system. MOSS ensures consistency and adaptability by
using a mechanism that maintains the Python context across interactions,
including isolation of local variables and preservation of runtime integrity.
At its core, the framework employs an Inversion of Control (IoC) container in
conjunction with decorators to enforce the least knowledge principle, allowing
agents to focus on abstract interfaces rather than concrete implementations.
This facilitates seamless integration of new tools and libraries, enables
runtime instance replacement, and reduces prompt complexity, providing a "what
you see is what you get" environment for the agent.
  Through a series of case studies, we show how this framework can enhance the
efficiency and capabilities of agent development and highlight its advantages
in moving towards Turing-complete agents capable of evolving through code.
