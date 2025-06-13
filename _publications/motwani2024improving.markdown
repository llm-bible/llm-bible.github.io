---
layout: publication
title: 'MALT: Improving Reasoning With Multi-agent LLM Training'
authors: Sumeet Ramesh Motwani, Chandler Smith, Rocktim Jyoti Das, Rafael Rafailov, Ivan Laptev, Philip H. S. Torr, Fabio Pizzati, Ronald Clark, Christian Schroeder De Witt
conference: "Arxiv"
year: 2024
bibkey: motwani2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.01928"}
tags: ['Agentic', 'Training Techniques', 'Reinforcement Learning']
---
Large Language Models (LLMs) often produce answers with a single
chain-of-thought, which restricts their ability to explore reasoning paths or
self-correct flawed outputs in complex tasks. In this paper, we introduce MALT
(Multi-Agent LLM Training), a novel post-training strategy that divides the
reasoning process into generation, verification, and refinement steps using a
sequential pipeline of heterogeneous agents. During data generation, each agent
is repeatedly sampled to form a multi-agent search tree, where final outputs
are graded against ground-truth data. We then apply value iteration to
propagate reward signals back to each role-conditioned model, automatically
producing multi-agent post-training data without human or teacher-model
supervision. Our off-policy approach allows each agent to specialize by
learning from correct and incorrect trajectories, ultimately improving the
end-to-end reasoning chain. On MATH, GSM8K, and CSQA, MALT surpasses the same
baseline LLM with a relative improvement of 15.66%, 7.42%, and 9.40%
respectively, making it an important advance towards multi-agent cooperative
training.
