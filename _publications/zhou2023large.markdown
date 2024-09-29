---
layout: publication
title: 'Large Language Model As A Policy Teacher For Training Reinforcement Learning Agents'
authors: Zhou Zihao, Hu Bin, Zhao Chenyang, Zhang Pu, Liu Bin
conference: "Arxiv"
year: 2023
bibkey: zhou2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13373"}
  - {name: "Code", url: "https://github.com/ZJLAB-AMMI/LLM4Teach"}
tags: ['Agent', 'Agentic', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent studies have uncovered the potential of Large Language Models (LLMs) in addressing complex sequential decision-making tasks through the provision of high-level instructions. However LLM-based agents lack specialization in tackling specific target problems particularly in real-time dynamic environments. Additionally deploying an LLM-based agent in practical scenarios can be both costly and time-consuming. On the other hand reinforcement learning (RL) approaches train agents that specialize in the target task but often suffer from low sampling efficiency and high exploration costs. In this paper we introduce a novel framework that addresses these challenges by training a smaller specialized student RL agent using instructions from an LLM-based teacher agent. By incorporating the guidance from the teacher agent the student agent can distill the prior knowledge of the LLM into its own model. Consequently the student agent can be trained with significantly less data. Moreover through further training with environment feedback the student agent surpasses the capabilities of its teacher for completing the target task. We conducted experiments on challenging MiniGrid and Habitat environments specifically designed for embodied AI research to evaluate the effectiveness of our framework. The results clearly demonstrate that our approach achieves superior performance compared to strong baseline methods. Our code is available at https://github.com/ZJLAB-AMMI/LLM4Teach."
