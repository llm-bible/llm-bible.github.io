---
layout: publication
title: 'GTR: Guided Thought Reinforcement Prevents Thought Collapse In Rl-based VLM Agent Training'
authors: Tong Wei, Yijun Yang, Junliang Xing, Yuanchun Shi, Zongqing Lu, Deheng Ye
conference: "Arxiv"
year: 2025
bibkey: wei2025guided
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08525"}
tags: ['Agentic', 'Multimodal Models', 'Training Techniques', 'Tools', 'Reinforcement Learning']
---
Reinforcement learning with verifiable outcome rewards (RLVR) has effectively
scaled up chain-of-thought (CoT) reasoning in large language models (LLMs).
Yet, its efficacy in training vision-language model (VLM) agents for
goal-directed action reasoning in visual environments is less established. This
work investigates this problem through extensive experiments on complex card
games, such as 24 points, and embodied tasks from ALFWorld. We find that when
rewards are based solely on action outcomes, RL fails to incentivize CoT
reasoning in VLMs, instead leading to a phenomenon we termed thought collapse,
characterized by a rapid loss of diversity in the agent's thoughts,
state-irrelevant and incomplete reasoning, and subsequent invalid actions,
resulting in negative rewards. To counteract thought collapse, we highlight the
necessity of process guidance and propose an automated corrector that evaluates
and refines the agent's reasoning at each RL step. This simple and scalable GTR
(Guided Thought Reinforcement) framework trains reasoning and action
simultaneously without the need for dense, per-step human labeling. Our
experiments demonstrate that GTR significantly enhances the performance and
generalization of the LLaVA-7b model across various visual environments,
achieving 3-5 times higher task success rates compared to SoTA models with
notably smaller model sizes.
