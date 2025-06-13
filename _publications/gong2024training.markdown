---
layout: publication
title: 'Training Agents With Weakly Supervised Feedback From Large Language Models'
authors: Dihong Gong, Pu Lu, Zelong Wang, Meng Zhou, Xiuqiang He
conference: "Arxiv"
year: 2024
bibkey: gong2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.19547"}
tags: ['Agentic', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Applications']
---
Large Language Models (LLMs) offer a promising basis for creating agents that
can tackle complex tasks through iterative environmental interaction. Existing
methods either require these agents to mimic expert-provided trajectories or
rely on definitive environmental feedback for reinforcement learning which
limits their application to specific scenarios like gaming or code generation.
This paper introduces a novel training method for LLM-based agents using weakly
supervised signals from a critic LLM, bypassing the need for expert
trajectories or definitive feedback. Our agents are trained in iterative
manner, where they initially generate trajectories through environmental
interaction. Subsequently, a critic LLM selects a subset of good trajectories,
which are then used to update the agents, enabling them to generate improved
trajectories in the next iteration. Extensive tests on the API-bank dataset
show consistent improvement in our agents' capabilities and comparable
performance to GPT-4, despite using open-source models with much fewer
parameters.
