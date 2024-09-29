---
layout: publication
title: Husky A Unified Open-Source Language Agent for Multi-Step Reasoning
authors: Kim Joongwon, Paranjape Bhargavi, Khot Tushar, Hajishirzi Hannaneh
conference: "Arxiv"
year: 2024
bibkey: kim2024husky
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.06469"}
  - {name: "Code", url: "https://github.com/agent-husky/Husky-v1"}
tags: ['Agentic', 'Applications', 'GPT', 'Has Code', 'Model Architecture', 'Tools']
---
Language agents perform complex tasks by using tools to execute each step precisely. However most existing agents are based on proprietary models or designed to target specific tasks such as mathematics or multi-hop question answering. We introduce Husky a holistic open-source language agent that learns to reason over a unified action space to address a diverse set of complex tasks involving numerical tabular and knowledge-based reasoning. Husky iterates between two stages 1) generating the next action to take towards solving a given task and 2) executing the action using expert models and updating the current solution state. We identify a thorough ontology of actions for addressing complex tasks and curate high-quality data to train expert models for executing these actions. Our experiments show that Husky outperforms prior language agents across 14 evaluation datasets. Moreover we introduce HuskyQA a new evaluation set which stress tests language agents for mixed-tool reasoning with a focus on retrieving missing knowledge and performing numerical reasoning. Despite using 7B models Husky matches or even exceeds frontier LMs such as GPT-4 on these tasks showcasing the efficacy of our holistic approach in addressing complex reasoning problems. Our code and models are available at https://github.com/agent-husky/Husky-v1.
