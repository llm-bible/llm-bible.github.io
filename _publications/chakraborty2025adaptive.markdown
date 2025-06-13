---
layout: publication
title: 'Adaptive Stress Testing Black-box LLM Planners'
authors: Neeloy Chakraborty, John Pohovey, Melkior Ornik, Katherine Driggs-campbell
conference: "Arxiv"
year: 2025
bibkey: chakraborty2025adaptive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.05665'}
tags: ['Reinforcement Learning', 'Prompting', 'Security', 'Responsible AI']
---
Large language models (LLMs) have recently demonstrated success in generalizing across decision-making tasks including planning, control and prediction, but their tendency to hallucinate unsafe and undesired outputs poses risks. We argue that detecting such failures is necessary, especially in safety-critical scenarios. Existing black-box methods often detect hallucinations by identifying inconsistencies across multiple samples. Many of these approaches typically introduce prompt perturbations like randomizing detail order or generating adversarial inputs, with the intuition that a confident model should produce stable outputs. We first perform a manual case study showing that other forms of perturbations (e.g., adding noise, removing sensor details) cause LLMs to hallucinate in a driving environment. We then propose a novel method for efficiently searching the space of prompt perturbations using Adaptive Stress Testing (AST) with Monte-Carlo Tree Search (MCTS). Our AST formulation enables discovery of scenarios and prompts that cause language models to act with high uncertainty. By generating MCTS prompt perturbation trees across diverse scenarios, we show that offline analyses can be used at runtime to automatically generate prompts that influence model uncertainty, and to inform real-time trust assessments of an LLM.
