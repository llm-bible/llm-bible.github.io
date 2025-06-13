---
layout: publication
title: 'Llm-explorer: A Plug-in Reinforcement Learning Policy Exploration Enhancement Driven By Large Language Models'
authors: Qianyue Hao, Yiwen Song, Qingmin Liao, Jian Yuan, Yong Li
conference: "Arxiv"
year: 2025
bibkey: hao2025llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.15293'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/LLM-Explorer-19BE'}
tags: ['Agentic', 'Has Code', 'RAG', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning']
---
Policy exploration is critical in reinforcement learning (RL), where existing approaches include greedy, Gaussian process, etc. However, these approaches utilize preset stochastic processes and are indiscriminately applied in all kinds of RL tasks without considering task-specific features that influence policy exploration. Moreover, during RL training, the evolution of such stochastic processes is rigid, which typically only incorporates a decay in the variance, failing to adjust flexibly according to the agent's real-time learning status. Inspired by the analyzing and reasoning capability of large language models (LLMs), we design LLM-Explorer to adaptively generate task-specific exploration strategies with LLMs, enhancing the policy exploration in RL. In our design, we sample the learning trajectory of the agent during the RL training in a given task and prompt the LLM to analyze the agent's current policy learning status and then generate a probability distribution for future policy exploration. Updating the probability distribution periodically, we derive a stochastic process specialized for the particular task and dynamically adjusted to adapt to the learning process. Our design is a plug-in module compatible with various widely applied RL algorithms, including the DQN series, DDPG, TD3, and any possible variants developed based on them. Through extensive experiments on the Atari and MuJoCo benchmarks, we demonstrate LLM-Explorer's capability to enhance RL policy exploration, achieving an average performance improvement up to 37.27%. Our code is open-source at https://anonymous.4open.science/r/LLM-Explorer-19BE for reproducibility.
