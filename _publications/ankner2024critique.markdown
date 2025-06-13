---
layout: publication
title: 'Critique-out-loud Reward Models'
authors: Zachary Ankner, Mansheej Paul, Brandon Cui, Jonathan D. Chang, Prithviraj Ammanabrolu
conference: "Arxiv"
year: 2024
bibkey: ankner2024critique
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11791"}
tags: ['Agentic', 'RAG', 'Tools', 'Reinforcement Learning']
---
Traditionally, reward models used for reinforcement learning from human
feedback (RLHF) are trained to directly predict preference scores without
leveraging the generation capabilities of the underlying large language model
(LLM). This limits the capabilities of reward models as they must reason
implicitly about the quality of a response, i.e., preference modeling must be
performed in a single forward pass through the model. To enable reward models
to reason explicitly about the quality of a response, we introduce
Critique-out-Loud (CLoud) reward models. CLoud reward models operate by first
generating a natural language critique of the assistant's response that is then
used to predict a scalar reward for the quality of the response. We demonstrate
the success of CLoud reward models for both Llama-3-8B and 70B base models:
compared to classic reward models CLoud reward models improve pairwise
preference classification accuracy on RewardBench by 4.65 and 5.84 percentage
points for the 8B and 70B base models respectively. Furthermore, CLoud reward
models lead to a Pareto improvement for win rate on ArenaHard when used as the
scoring model for Best-of-N. Finally, we explore how to exploit the dynamic
inference compute capabilities of CLoud reward models by performing
self-consistency decoding for reward prediction.
