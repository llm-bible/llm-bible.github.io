---
layout: publication
title: 'Zero-shot Compositional Policy Learning Via Language Grounding'
authors: Tianshi Cao, Jingkang Wang, Yining Zhang, Sivabalan Manivasagam
conference: "Arxiv"
year: 2020
bibkey: cao2020zero
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2004.07200"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'Transformer', 'Attention Mechanism']
---
Despite recent breakthroughs in reinforcement learning (RL) and imitation
learning (IL), existing algorithms fail to generalize beyond the training
environments. In reality, humans can adapt to new tasks quickly by leveraging
prior knowledge about the world such as language descriptions. To facilitate
the research on language-guided agents with domain adaption, we propose a novel
zero-shot compositional policy learning task, where the environments are
characterized as a composition of different attributes. Since there are no
public environments supporting this study, we introduce a new research platform
BabyAI++ in which the dynamics of environments are disentangled from visual
appearance. At each episode, BabyAI++ provides varied vision-dynamics
combinations along with corresponding descriptive texts. To evaluate the
adaption capability of learned agents, a set of vision-dynamics pairings are
held-out for testing on BabyAI++. Unsurprisingly, we find that current
language-guided RL/IL techniques overfit to the training environments and
suffer from a huge performance drop when facing unseen combinations. In
response, we propose a multi-modal fusion method with an attention mechanism to
perform visual language-grounding. Extensive experiments show strong evidence
that language grounding is able to improve the generalization of agents across
environments with varied dynamics.
