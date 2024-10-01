---
layout: publication
title: 'Game Development As Human-llm Interaction'
authors: Hong Jiale, Wu Hongqiu, Zhao Hai
conference: "Arxiv"
year: 2024
bibkey: hong2024game
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09386"}
  - {name: "Code", url: "https://github.com/alterego238/IGE"}
tags: ['Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
"Game development is a highly specialized task that relies on a complex game engine powered by complex programming languages, preventing many gaming enthusiasts from handling it. This paper introduces the Interaction-driven Game Engine (IGE) powered by LLM, which allows everyone to develop a custom game using natural language through Human-LLM interaction. To enable an LLM to function as an IGE, we instruct it to perform the following processes in each turn: (1) \(P_{script}\) : configure the game script segment based on the user's input; (2) \(P_{code}\) : generate the corresponding code snippet based on the game script segment; (3) \(P_{utter}\) : interact with the user, including guidance and feedback. We propose a data synthesis pipeline based on the LLM to generate game script-code pairs and interactions from a few manually crafted seed data. We propose a three-stage progressive training strategy to transfer the dialogue-based LLM to our IGE smoothly. We construct an IGE for poker games as a case study and comprehensively evaluate it from two perspectives: interaction quality and code correctness. The code and data are available at \url\{https://github.com/alterego238/IGE\}."
