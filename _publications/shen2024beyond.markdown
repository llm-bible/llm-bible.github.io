---
layout: publication
title: 'Beyond Human Preferences: Exploring Reinforcement Learning Trajectory Evaluation And Improvement Through Llms'
authors: Zichao Shen, Tianchen Zhu, Qingyun Sun, Shiqi Gao, Jianxin Li
conference: "Arxiv"
year: 2024
bibkey: shen2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19644"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning']
---
Reinforcement learning (RL) faces challenges in evaluating policy
trajectories within intricate game tasks due to the difficulty in designing
comprehensive and precise reward functions. This inherent difficulty curtails
the broader application of RL within game environments characterized by diverse
constraints. Preference-based reinforcement learning (PbRL) presents a
pioneering framework that capitalizes on human preferences as pivotal reward
signals, thereby circumventing the need for meticulous reward engineering.
However, obtaining preference data from human experts is costly and
inefficient, especially under conditions marked by complex constraints. To
tackle this challenge, we propose a LLM-enabled automatic preference generation
framework named LLM4PG , which harnesses the capabilities of large language
models (LLMs) to abstract trajectories, rank preferences, and reconstruct
reward functions to optimize conditioned policies. Experiments on tasks with
complex language constraints demonstrated the effectiveness of our LLM-enabled
reward functions, accelerating RL convergence and overcoming stagnation caused
by slow or absent progress under original reward structures. This approach
mitigates the reliance on specialized human knowledge and demonstrates the
potential of LLMs to enhance RL's effectiveness in complex environments in the
wild.
