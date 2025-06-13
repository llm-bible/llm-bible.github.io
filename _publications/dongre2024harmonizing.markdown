---
layout: publication
title: 'Respact: Harmonizing Reasoning, Speaking, And Acting Towards Building Large Language Model-based Conversational AI Agents'
authors: Vardhan Dongre, Xiaocheng Yang, Emre Can Acikgoz, Suvodip Dey, Gokhan Tur, Dilek Hakkani-tür
conference: "Arxiv"
year: 2024
bibkey: dongre2024harmonizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.00927"}
tags: ['Agentic', 'Applications', 'Tools', 'Reinforcement Learning']
---
Large language model (LLM)-based agents are increasingly employed to interact
with external environments (e.g., games, APIs, world models) to solve
user-provided tasks. However, current frameworks often lack the ability to
collaborate effectively with users in fully conversational settings.
Conversations are essential for aligning on task details, achieving
user-defined goals, and satisfying preferences. While existing agents address
ambiguity through clarification questions, they underutilize the broader
potential of an LLM's conversational capabilities. In this work, we introduce
ReSpAct, an LLM-based agent designed to seamlessly integrate reasoning,
decision-making, and dynamic dialogue for task-solving. Expanding on
reasoning-first approaches like ReAct, ReSpAct employs active, free-flowing
dialogues to interpret instructions, clarify goals, provide status updates,
resolve subtask failures, and refine plans based on user inputs without any
explicit dialogue schema. By alternating between task-solving actions and
interactive conversations, ReSpAct demonstrates improved performance across
diverse environments. We evaluate ReSpAct in user-interactive settings,
including task-oriented dialogue systems (MultiWOZ) and decision-making tasks
(ALFWorld, WebShop). ReSpAct outperforms ReAct with absolute success rate
improvements of 6% and 4% in ALFWorld and WebShop, respectively, and achieves a
5.5% gain in Inform and a 3% gain in Success scores in MultiWOZ. These results
highlight the value of integrating dynamic user-agent collaboration for more
effective task resolution.
