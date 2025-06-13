---
layout: publication
title: 'R-search: Empowering LLM Reasoning With Search Via Multi-reward Reinforcement Learning'
authors: Qingfei Zhao, Ruobing Wang, Dingling Xu, Daren Zha, Limin Liu
conference: "Arxiv"
year: 2025
bibkey: zhao2025r
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04185"}
  - {name: "Code", url: "https://github.com/QingFei1/R-Search"}
tags: ['Agentic', 'Tools', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Has Code']
---
Large language models (LLMs) have notably progressed in multi-step and long-chain reasoning. However, extending their reasoning capabilities to encompass deep interactions with search remains a non-trivial challenge, as models often fail to identify optimal reasoning-search interaction trajectories, resulting in suboptimal responses. We propose R-Search, a novel reinforcement learning framework for Reasoning-Search integration, designed to enable LLMs to autonomously execute multi-step reasoning with deep search interaction, and learn optimal reasoning search interaction trajectories via multi-reward signals, improving response quality in complex logic- and knowledge-intensive tasks. R-Search guides the LLM to dynamically decide when to retrieve or reason, while globally integrating key evidence to enhance deep knowledge interaction between reasoning and search. During RL training, R-Search provides multi-stage, multi-type rewards to jointly optimize the reasoning-search trajectory. Experiments on seven datasets show that R-Search outperforms advanced RAG baselines by up to 32.2% (in-domain) and 25.1% (out-of-domain). The code and data are available at https://github.com/QingFei1/R-Search.
