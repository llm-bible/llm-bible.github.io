---
layout: publication
title: 'Graph-enhanced Large Language Models In Asynchronous Plan Reasoning'
authors: Fangru Lin, Emanuele La Malfa, Valentin Hofmann, Elle Michelle Yang, Anthony Cohn, Janet B. Pierrehumbert
conference: "Arxiv"
year: 2024
bibkey: lin2024graph
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02805"}
  - {name: "Code", url: "https://github.com/fangru-lin/graph-llm-asynchow-plan"}
tags: ['Agentic', 'Agent', 'Model Architecture', 'Reinforcement Learning', 'GPT', 'Has Code', 'Prompting']
---
Planning is a fundamental property of human intelligence. Reasoning about
asynchronous plans is challenging since it requires sequential and parallel
planning to optimize time costs. Can large language models (LLMs) succeed at
this task? Here, we present the first large-scale study investigating this
question. We find that a representative set of closed and open-source LLMs,
including GPT-4 and LLaMA-2, behave poorly when not supplied with illustrations
about the task-solving process in our benchmark AsyncHow. We propose a novel
technique called Plan Like a Graph (PLaG) that combines graphs with natural
language prompts and achieves state-of-the-art results. We show that although
PLaG can boost model performance, LLMs still suffer from drastic degradation
when task complexity increases, highlighting the limits of utilizing LLMs for
simulating digital devices. We see our study as an exciting step towards using
LLMs as efficient autonomous agents. Our code and data are available at
https://github.com/fangru-lin/graph-llm-asynchow-plan.
