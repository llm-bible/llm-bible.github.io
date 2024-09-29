---
layout: publication
title: 'Dialogue Action Tokens: Steering Language Models In Goal-directed Dialogue With A Multi-turn Planner'
authors: Li Kenneth, Wang Yiming, Viégas Fernanda, Wattenberg Martin
conference: "Arxiv"
year: 2024
bibkey: li2024dialogue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11978"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Security', 'Tools']
---
We present an approach called Dialogue Action Tokens (DAT) that adapts language model agents to plan goal-directed dialogues. The core idea is to treat each utterance as an action thereby converting dialogues into games where existing approaches such as reinforcement learning can be applied. Specifically we freeze a pretrained language model and train a small planner model that predicts a continuous action vector used for controlled generation in each round. This design avoids the problem of language degradation under reward optimization. When evaluated on the Sotopia platform for social simulations the DAT-steered LLaMA model surpasses GPT-4s performance. We also apply DAT to steer an attacker language model in a novel multi-turn red-teaming setting revealing a potential new attack surface.
