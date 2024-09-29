---
layout: publication
title: Lifelong Robot Library Learning Bootstrapping Composable And Generalizable Skills For Embodied Control With Language Models
authors: Tziafas Georgios, Kasaei Hamidreza
conference: "Arxiv"
year: 2024
bibkey: tziafas2024lifelong
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18746"}
  - {name: "Code", url: "https://gtziafas.github.io/LRLL&#95;project"}
tags: ['Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Large Language Models (LLMs) have emerged as a new paradigm for embodied reasoning and control most recently by generating robot policy code that utilizes a custom library of vision and control primitive skills. However prior arts fix their skills library and steer the LLM with carefully hand45;crafted prompt engineering limiting the agent to a stationary range of addressable tasks. In this work we introduce LRLL an LLM45;based lifelong learning agent that continuously grows the robot skill library to tackle manipulation tasks of ever45;growing complexity. LRLL achieves this with four novel contributions 1) a soft memory module that allows dynamic storage and retrieval of past experiences to serve as context 2) a self45;guided exploration policy that proposes new tasks in simulation 3) a skill abstractor that distills recent experiences into new library skills and 4) a lifelong learning algorithm for enabling human users to bootstrap new skills with minimal online interaction. LRLL continuously transfers knowledge from the memory to the library building composable general and interpretable policies while bypassing gradient45;based optimization thus relieving the learner from catastrophic forgetting. Empirical evaluation in a simulated tabletop environment shows that LRLL outperforms end45;to45;end and vanilla LLM approaches in the lifelong setup while learning skills that are transferable to the real world. Project material will become available at the webpage https://gtziafas.github.io/LRLL&#95;project.
