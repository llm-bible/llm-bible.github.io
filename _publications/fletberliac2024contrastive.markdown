---
layout: publication
title: Contrastive Policy Gradient&#58; Aligning Llms On Sequence-level Scores In A Supervised-friendly Fashion
authors: Flet-berliac Yannis, Grinsztajn Nathan, Strub Florian, Choi Eugene, Cremer Chris, Ahmadian Arash, Chandak Yash, Azar Mohammad Gheshlaghi, Pietquin Olivier, Geist Matthieu
conference: "Arxiv"
year: 2024
bibkey: fletberliac2024contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.19185"}
tags: ['Agentic', 'Applications', 'Efficiency And Optimization', 'Reinforcement Learning']
---
Reinforcement Learning (RL) has been used to finetune Large Language Models (LLMs) using a reward model trained from preference data to better align with human judgment. The recently introduced direct alignment methods which are often simpler more stable and computationally lighter can more directly achieve this. However these approaches cannot optimize arbitrary rewards and the preference-based ones are not the only rewards of interest for LLMs (eg. unit tests for code generation or textual entailment for summarization among others). RL-finetuning is usually done with a variation of policy gradient which calls for on-policy or near-on-policy samples requiring costly generations. We introduce Contrastive Policy Gradient or CoPG a simple and mathematically principled new RL algorithm that can estimate the optimal policy even from off-policy data. It can be seen as an off-policy policy gradient approach that does not rely on important sampling techniques and highlights the importance of using (the right) state baseline. We show this approach to generalize the direct alignment method IPO (identity preference optimization) and classic policy gradient. We experiment with the proposed CoPG on a toy bandit problem to illustrate its properties as well as for finetuning LLMs on a summarization task using a learned reward function considered as ground truth for the purpose of the experiments.
