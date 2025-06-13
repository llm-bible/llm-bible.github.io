---
layout: publication
title: 'Language Agents With Reinforcement Learning For Strategic Play In The Werewolf Game'
authors: Zelai Xu, Chao Yu, Fei Fang, Yu Wang, Yi Wu
conference: "Arxiv"
year: 2023
bibkey: xu2023language
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.18940'}
tags: ['Agentic', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'Ethics and Bias']
---
Agents built with large language models (LLMs) have shown great potential across a wide range of domains. However, in complex decision-making tasks, pure LLM-based agents tend to exhibit intrinsic bias in their choice of actions, which is inherited from the model's training data and results in suboptimal performance. To develop strategic language agents, i.e., agents that generate flexible language actions and possess strong decision-making abilities, we propose a novel framework that powers LLM-based agents with reinforcement learning (RL). We consider Werewolf, a popular social deduction game, as a challenging testbed that emphasizes versatile communication and strategic gameplay. To mitigate the intrinsic bias in language actions, our agents use an LLM to perform deductive reasoning and generate a diverse set of action candidates. Then an RL policy trained to optimize the decision-making ability chooses an action from the candidates to play in the game. Extensive experiments show that our agents overcome the intrinsic bias and outperform existing LLM-based agents in the Werewolf game. We also conduct human-agent experiments and find that our agents achieve human-level performance and demonstrate strong strategic play.
