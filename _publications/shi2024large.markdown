---
layout: publication
title: Large Language Models Are Learnable Planners For Long45;term Recommendation
authors: Shi Wentao, He Xiangnan, Zhang Yang, Gao Chongming, Li Xinyue, Zhang Jizhi, Wang Qifan, Feng Fuli
conference: "Arxiv"
year: 2024
bibkey: shi2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.00843"}
  - {name: "Code", url: "https://github.com/jizhi&#45;zhang/BiLLP"}
tags: ['Agentic', 'Has Code', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Planning for both immediate and long45;term benefits becomes increasingly important in recommendation. Existing methods apply Reinforcement Learning (RL) to learn planning capacity by maximizing cumulative reward for long45;term recommendation. However the scarcity of recommendation data presents challenges such as instability and susceptibility to overfitting when training RL models from scratch resulting in sub45;optimal performance. In this light we propose to leverage the remarkable planning capabilities over sparse data of Large Language Models (LLMs) for long45;term recommendation. The key to achieving the target lies in formulating a guidance plan following principles of enhancing long45;term engagement and grounding the plan to effective and executable actions in a personalized manner. To this end we propose a Bi45;level Learnable LLM Planner framework which consists of a set of LLM instances and breaks down the learning process into macro45;learning and micro45;learning to learn macro45;level guidance and micro45;level personalized recommendation policies respectively. Extensive experiments validate that the framework facilitates the planning ability of LLMs for long45;term recommendation. Our code and data can be found at https://github.com/jizhi&#45;zhang/BiLLP.
