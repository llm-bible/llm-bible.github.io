---
layout: publication
title: 'Arpo:end-to-end Policy Optimization For GUI Agents With Experience Replay'
authors: Fanbin Lu, Zhisheng Zhong, Shu Liu, Chi-wing Fu, Jiaya Jia
conference: "Arxiv"
year: 2025
bibkey: lu2025policy
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16282'}
  - {name: "Code", url: 'https://github.com/dvlab-research/ARPO.git'}
tags: ['Agentic', 'Has Code', 'Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning']
---
Training large language models (LLMs) as interactive agents for controlling graphical user interfaces (GUIs) presents a unique challenge to optimize long-horizon action sequences with multimodal feedback from complex environments. While recent works have advanced multi-turn reinforcement learning (RL) for reasoning and tool-using capabilities in LLMs, their application to GUI-based agents remains relatively underexplored due to the difficulty of sparse rewards, delayed feedback, and high rollout costs. In this paper, we investigate end-to-end policy optimization for vision-language-based GUI agents with the aim of improving performance on complex, long-horizon computer tasks. We propose Agentic Replay Policy Optimization (ARPO), an end-to-end RL approach that augments Group Relative Policy Optimization (GRPO) with a replay buffer to reuse the successful experience across training iterations. To further stabilize the training process, we propose a task selection strategy that filters tasks based on baseline agent performance, allowing the agent to focus on learning from informative interactions. Additionally, we compare ARPO with offline preference optimization approaches, highlighting the advantages of policy-based methods in GUI environments. Experiments on the OSWorld benchmark demonstrate that ARPO achieves competitive results, establishing a new performance baseline for LLM-based GUI agents trained via reinforcement learning. Our findings underscore the effectiveness of reinforcement learning for training multi-turn, vision-language GUI agents capable of managing complex real-world UI interactions. Codes and models:https://github.com/dvlab-research/ARPO.git.
