---
layout: publication
title: 'Retrieval-augmented Decision Transformer: External Memory For In-context RL'
authors: Thomas Schmied, Fabian Paischer, Vihang Patil, Markus Hofmarcher, Razvan Pascanu, Sepp Hochreiter
conference: "Arxiv"
year: 2024
bibkey: schmied2024retrieval
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.07071'}
tags: ['Agentic', 'Transformer', 'RAG', 'Training Techniques', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'In-Context Learning', 'Pretraining Methods']
---
In-context learning (ICL) is the ability of a model to learn a new task by
observing a few exemplars in its context. While prevalent in NLP, this
capability has recently also been observed in Reinforcement Learning (RL)
settings. Prior in-context RL methods, however, require entire episodes in the
agent's context. Given that complex environments typically lead to long
episodes with sparse rewards, these methods are constrained to simple
environments with short episodes. To address these challenges, we introduce
Retrieval-Augmented Decision Transformer (RA-DT). RA-DT employs an external
memory mechanism to store past experiences from which it retrieves only
sub-trajectories relevant for the current situation. The retrieval component in
RA-DT does not require training and can be entirely domain-agnostic. We
evaluate the capabilities of RA-DT on grid-world environments, robotics
simulations, and procedurally-generated video games. On grid-worlds, RA-DT
outperforms baselines, while using only a fraction of their context length.
Furthermore, we illuminate the limitations of current in-context RL methods on
complex environments and discuss future directions. To facilitate future
research, we release datasets for four of the considered environments.
