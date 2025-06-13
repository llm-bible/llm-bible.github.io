---
layout: publication
title: 'Reinforced Prompt Personalization For Recommendation With Large Language Models'
authors: Wenyu Mao, Jiancan Wu, Weijian Chen, Chongming Gao, Xiang Wang, Xiangnan He
conference: "Arxiv"
year: 2024
bibkey: mao2024reinforced
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.17115"}
  - {name: "Code", url: "https://github.com/maowenyu-11/RPP"}
tags: ['Agentic', 'Efficiency and Optimization', 'Reinforcement Learning', 'Has Code', 'Few-Shot', 'Prompting']
---
Designing effective prompts can empower LLMs to understand user preferences
and provide recommendations with intent comprehension and knowledge utilization
capabilities. Nevertheless, recent studies predominantly concentrate on
task-wise prompting, developing fixed prompt templates shared across all users
in a given recommendation task (e.g., rating or ranking). Although convenient,
task-wise prompting overlooks individual user differences, leading to
inaccurate analysis of user interests. In this work, we introduce the concept
of instance-wise prompting, aiming at personalizing discrete prompts for
individual users. Toward this end, we propose Reinforced Prompt Personalization
(RPP) to realize it automatically. To improve efficiency and quality, RPP
personalizes prompts at the sentence level rather than searching in the vast
vocabulary word-by-word. Specifically, RPP breaks down the prompt into four
patterns, tailoring patterns based on multi-agent and combining them. Then the
personalized prompts interact with LLMs (environment) iteratively, to boost
LLMs' recommending performance (reward). In addition to RPP, to improve the
scalability of action space, our proposal of RPP+ dynamically refines the
selected actions with LLMs throughout the iterative process. Extensive
experiments on various datasets demonstrate the superiority of RPP/RPP+ over
traditional recommender models, few-shot methods, and other prompt-based
methods, underscoring the significance of instance-wise prompting in LLMs for
recommendation. Our code is available at https://github.com/maowenyu-11/RPP.
