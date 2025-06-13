---
layout: publication
title: 'Extracting Heuristics From Large Language Models For Reward Shaping In Reinforcement Learning'
authors: Siddhant Bhambri, Amrita Bhattacharjee, Durgesh Kalwar, Lin Guan, Huan Liu, Subbarao Kambhampati
conference: "Arxiv"
year: 2024
bibkey: bhambri2024extracting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.15194"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'RAG']
---
Reinforcement Learning (RL) suffers from sample inefficiency in sparse reward
domains, and the problem is further pronounced in case of stochastic
transitions. To improve the sample efficiency, reward shaping is a well-studied
approach to introduce intrinsic rewards that can help the RL agent converge to
an optimal policy faster. However, designing a useful reward shaping function
for all desirable states in the Markov Decision Process (MDP) is challenging,
even for domain experts. Given that Large Language Models (LLMs) have
demonstrated impressive performance across a magnitude of natural language
tasks, we aim to answer the following question: `Can we obtain heuristics using
LLMs for constructing a reward shaping function that can boost an RL agent's
sample efficiency?' To this end, we aim to leverage off-the-shelf LLMs to
generate a plan for an abstraction of the underlying MDP. We further use this
LLM-generated plan as a heuristic to construct the reward shaping signal for
the downstream RL agent. By characterizing the type of abstraction based on the
MDP horizon length, we analyze the quality of heuristics when generated using
an LLM, with and without a verifier in the loop. Our experiments across
multiple domains with varying horizon length and number of sub-goals from the
BabyAI environment suite, Household, Mario, and, Minecraft domain, show 1) the
advantages and limitations of querying LLMs with and without a verifier to
generate a reward shaping heuristic, and, 2) a significant improvement in the
sample efficiency of PPO, A2C, and Q-learning when guided by the LLM-generated
heuristics.
