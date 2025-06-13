---
layout: publication
title: 'SAC-GLAM: Improving Online RL For LLM Agents With Soft Actor-critic And Hindsight Relabeling'
authors: Loris Gaven, Clement Romac, Thomas Carta, Sylvain Lamprier, Olivier Sigaud, Pierre-yves Oudeyer
conference: "Arxiv"
year: 2024
bibkey: gaven2024sac
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12481"}
tags: ['Agentic', 'Fine-Tuning', 'Reinforcement Learning']
---
The past years have seen Large Language Models (LLMs) strive not only as
generative models but also as agents solving textual sequential decision-making
tasks. When facing complex environments where their zero-shot abilities are
insufficient, recent work showed online Reinforcement Learning (RL) could be
used for the LLM agent to discover and learn efficient strategies
interactively. However, most prior work sticks to on-policy algorithms, which
greatly reduces the scope of methods such agents could use for both exploration
and exploitation, such as experience replay and hindsight relabeling. Yet, such
methods may be key for LLM learning agents, and in particular when designing
autonomous intrinsically motivated agents sampling and pursuing their own goals
(i.e. autotelic agents). This paper presents and studies an adaptation of Soft
Actor-Critic and hindsight relabeling to LLM agents. Our method not only paves
the path towards autotelic LLM agents that learn online but can also outperform
on-policy methods in more classic multi-goal RL environments.
