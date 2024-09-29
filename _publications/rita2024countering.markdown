---
layout: publication
title: 'Countering Reward Over-optimization In LLM With Demonstration-guided Reinforcement Learning'
authors: Rita Mathieu, Strub Florian, Chaabouni Rahma, Michel Paul, Dupoux Emmanuel, Pietquin Olivier
conference: "Arxiv"
year: 2024
bibkey: rita2024countering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.19409"}
tags: ['Agentic', 'Efficiency And Optimization', 'Prompting', 'RAG', 'Reinforcement Learning']
---
While Reinforcement Learning (RL) has been proven essential for tuning large language models (LLMs) it can lead to reward over-optimization (ROO). Existing approaches address ROO by adding KL regularization requiring computationally expensive hyperparameter tuning. Additionally KL regularization focuses solely on regularizing the language policy neglecting a potential source of regularization the reward function itself. Inspired by demonstration-guided RL we here introduce the Reward Calibration from Demonstration (RCfD) which leverages human demonstrations and a reward model to recalibrate the reward objective. Formally given a prompt the RCfD objective minimizes the distance between the demonstrations and LLMs rewards rather than directly maximizing the reward function. This objective shift avoids incentivizing the LLM to exploit the reward model and promotes more natural and diverse language generation. We show the effectiveness of RCfD on three language tasks which achieves comparable performance to carefully tuned baselines while mitigating ROO.
