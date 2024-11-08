---
layout: publication
title: 'Offline Training Of Language Model Agents With Functions As Learnable Weights'
authors: Zhang Shaokun, Zhang Jieyu, Liu Jiale, Song Linxin, Wang Chi, Krishna Ranjay, Wu Qingyun
conference: "Arxiv"
year: 2024
bibkey: zhang2024offline
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11359"}
tags: ['Agentic', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Researchers and practitioners have recently reframed powerful Large Language
Models (LLMs) as agents, enabling them to automate complex tasks largely via
the use of specialized functions. To facilitate the development of LLM agents,
we present a novel paradigm of training LLM agents without modifying the LLM
weights, which is particularly useful when the LLMs are difficult or
inaccessible for modifications. Inspired by how humans continuously forge tools
to adapt to real-world tasks, rather than change our biological structure to
fit a static set of tools, we propose to progressively forge agent's functions
to better solve the downstream tasks instead of modifying the LLM weights. By
treating the functions as learnable `agent parameters' and leveraging the
fundamental idea of model training in artificial intelligence, we develop
AgentOptimizer that employs the LLM to update agents' functions and devise an
agent training algorithm with two strategies, roll-back, and early-stop, to
streamline the training process. With extensive experiments, we showcase that
the agent training paradigm could significantly improve the performance of
representative LLM agents in various downstream tasks. We also study the
behavior of the agent training regarding aspects like the learning curve and
domain transferability.
