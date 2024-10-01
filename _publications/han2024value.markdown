---
layout: publication
title: 'Value Augmented Sampling For Language Model Alignment And Personalization'
authors: Han Seungwook, Shenfeld Idan, Srivastava Akash, Kim Yoon, Agrawal Pulkit
conference: "Arxiv"
year: 2024
bibkey: han2024value
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06639"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Aligning Large Language Models (LLMs) to cater to different human preferences, learning new skills, and unlearning harmful behavior is an important problem. Search-based methods, such as Best-of-N or Monte-Carlo Tree Search, are performant, but impractical for LLM adaptation due to their high inference cost. On the other hand, using Reinforcement Learning (RL) for adaptation is computationally efficient, but performs worse due to the optimization challenges in co-training the value function and the policy. We present a new framework for reward optimization, Value Augmented Sampling (VAS), that can maximize different reward functions using data sampled from only the initial, frozen LLM. VAS solves for the optimal reward-maximizing policy without co-training the policy and the value function, making the optimization stable, outperforming established baselines, such as PPO and DPO, on standard benchmarks, and achieving comparable results to Best-of-128 with lower inference cost. Unlike existing RL methods that require changing the weights of the LLM, VAS does not require access to the weights of the pre-trained LLM. Thus, it can even adapt LLMs (e.g., ChatGPT), which are available only as APIs. In addition, our algorithm unlocks the new capability of composing several rewards and controlling the extent of each one during deployment time, paving the road ahead for the future of aligned, personalized LLMs.
