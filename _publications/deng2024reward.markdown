---
layout: publication
title: 'Reward Guidance For Reinforcement Learning Tasks Based On Large Language Models: The LMGT Framework'
authors: Yongxin Deng, Xihe Qiu, Jue Chen, Xiaoyu Tan
conference: "Arxiv"
year: 2024
bibkey: deng2024reward
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.04744'}
tags: ['Agentic', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Reinforcement Learning']
---
The inherent uncertainty in the environmental transition model of Reinforcement Learning (RL) necessitates a delicate balance between exploration and exploitation. This balance is crucial for optimizing computational resources to accurately estimate expected rewards for the agent. In scenarios with sparse rewards, such as robotic control systems, achieving this balance is particularly challenging. However, given that many environments possess extensive prior knowledge, learning from the ground up in such contexts may be redundant. To address this issue, we propose Language Model Guided reward Tuning (LMGT), a novel, sample-efficient framework. LMGT leverages the comprehensive prior knowledge embedded in Large Language Models (LLMs) and their proficiency in processing non-standard data forms, such as wiki tutorials. By utilizing LLM-guided reward shifts, LMGT adeptly balances exploration and exploitation, thereby guiding the agent's exploratory behavior and enhancing sample efficiency. We have rigorously evaluated LMGT across various RL tasks and evaluated it in the embodied robotic environment Housekeep. Our results demonstrate that LMGT consistently outperforms baseline methods. Furthermore, the findings suggest that our framework can substantially reduce the computational resources required during the RL training phase.
