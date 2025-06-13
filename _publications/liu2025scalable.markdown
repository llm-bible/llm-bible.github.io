---
layout: publication
title: 'Scalable In-context Q-learning'
authors: Jinmei Liu, Fuhong Liu, Jianye Hao, Bo Wang, Huaxiong Li, Chunlin Chen, Zhi Wang
conference: "Arxiv"
year: 2025
bibkey: liu2025scalable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01299"}
  - {name: "Code", url: "https://github.com/NJU-RL/SICQL"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Has Code', 'Prompting', 'In-Context Learning']
---
Recent advancements in language models have demonstrated remarkable in-context learning abilities, prompting the exploration of in-context reinforcement learning (ICRL) to extend the promise to decision domains. Due to involving more complex dynamics and temporal correlations, existing ICRL approaches may face challenges in learning from suboptimal trajectories and achieving precise in-context inference. In the paper, we propose \textbf\{S\}calable \textbf\{I\}n-\textbf\{C\}ontext \textbf\{Q\}-\textbf\{L\}earning (\textbf\{SICQL\}), an innovative framework that harnesses dynamic programming and world modeling to steer ICRL toward efficient reward maximization and task generalization, while retaining the scalability and stability of supervised pretraining. We design a prompt-based multi-head transformer architecture that simultaneously predicts optimal policies and in-context value functions using separate heads. We pretrain a generalized world model to capture task-relevant information, enabling the construction of a compact prompt that facilitates fast and precise in-context inference. During training, we perform iterative policy improvement by fitting a state value function to an upper-expectile of the Q-function, and distill the in-context value functions into policy extraction using advantage-weighted regression. Extensive experiments across a range of discrete and continuous environments show consistent performance gains over various types of baselines, especially when learning from suboptimal data. Our code is available at https://github.com/NJU-RL/SICQL
