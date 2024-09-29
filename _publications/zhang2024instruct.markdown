---
layout: publication
title: Instruct Large Language Models To Drive Like Humans
authors: Zhang Ruijun, Guo Xianda, Zheng Wenzhao, Zhang Chenming, Keutzer Kurt, Chen Long
conference: "Arxiv"
year: 2024
bibkey: zhang2024instruct
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07296"}
  - {name: "Code", url: "https://github.com/bonbon-rj/InstructDriver"}
tags: ['Has Code', 'Interpretability And Explainability', 'Pretraining Methods', 'Reinforcement Learning']
---
Motion planning in complex scenarios is the core challenge in autonomous driving. Conventional methods apply predefined rules or learn from driving data to plan the future trajectory. Recent methods seek the knowledge preserved in large language models (LLMs) and apply them in the driving scenarios. Despite the promising results it is still unclear whether the LLM learns the underlying human logic to drive. In this paper we propose an InstructDriver method to transform LLM into a motion planner with explicit instruction tuning to align its behavior with humans. We derive driving instruction data based on human logic (e.g. do not cause collisions) and traffic rules (e.g. proceed only when green lights). We then employ an interpretable InstructChain module to further reason the final planning reflecting the instructions. Our InstructDriver allows the injection of human rules and learning from driving data enabling both interpretability and data scalability. Different from existing methods that experimented on closed-loop or simulated settings we adopt the real-world closed-loop motion planning nuPlan benchmark for better evaluation. InstructDriver demonstrates the effectiveness of the LLM planner in a real-world closed-loop setting. Our code is publicly available at https://github.com/bonbon-rj/InstructDriver."
