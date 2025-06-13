---
layout: publication
title: 'Hackphyr: A Local Fine-tuned LLM Agent For Network Security Environments'
authors: Maria Rigaki, Carlos Catania, Sebastian Garcia
conference: "Arxiv"
year: 2024
bibkey: rigaki2024local
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11276"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Security']
---
Large Language Models (LLMs) have shown remarkable potential across various
domains, including cybersecurity. Using commercial cloud-based LLMs may be
undesirable due to privacy concerns, costs, and network connectivity
constraints. In this paper, we present Hackphyr, a locally fine-tuned LLM to be
used as a red-team agent within network security environments. Our fine-tuned 7
billion parameter model can run on a single GPU card and achieves performance
comparable with much larger and more powerful commercial models such as GPT-4.
Hackphyr clearly outperforms other models, including GPT-3.5-turbo, and
baselines, such as Q-learning agents in complex, previously unseen scenarios.
To achieve this performance, we generated a new task-specific cybersecurity
dataset to enhance the base model's capabilities. Finally, we conducted a
comprehensive analysis of the agents' behaviors that provides insights into the
planning abilities and potential shortcomings of such agents, contributing to
the broader understanding of LLM-based agents in cybersecurity contexts
