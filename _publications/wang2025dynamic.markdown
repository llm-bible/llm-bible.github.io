---
layout: publication
title: 'DYSTIL: Dynamic Strategy Induction With Large Language Models For Reinforcement Learning'
authors: Borui Wang, Kathleen Mckeown, Rex Ying
conference: "Arxiv"
year: 2025
bibkey: wang2025dynamic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.03209'}
tags: ['Agentic', 'Interpretability and Explainability', 'RAG', 'Efficiency and Optimization', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Interpretability']
---
Reinforcement learning from expert demonstrations has long remained a
challenging research problem, and existing state-of-the-art methods using
behavioral cloning plus further RL training often suffer from poor
generalization, low sample efficiency, and poor model interpretability.
Inspired by the strong reasoning abilities of large language models (LLMs), we
propose a novel strategy-based reinforcement learning framework integrated with
LLMs called DYnamic STrategy Induction with Llms for reinforcement learning
(DYSTIL) to overcome these limitations. DYSTIL dynamically queries a
strategy-generating LLM to induce textual strategies based on advantage
estimations and expert demonstrations, and gradually internalizes induced
strategies into the RL agent through policy optimization to improve its
performance through boosting policy generalization and enhancing sample
efficiency. It also provides a direct textual channel to observe and interpret
the evolution of the policy's underlying strategies during training. We test
DYSTIL over challenging RL environments from Minigrid and BabyAI, and
empirically demonstrate that DYSTIL significantly outperforms state-of-the-art
baseline methods by 17.75% in average success rate while also enjoying higher
sample efficiency during the learning process.
