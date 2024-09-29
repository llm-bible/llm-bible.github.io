---
layout: publication
title: Continual Skill And Task Learning Via Dialogue
authors: Gu Weiwei, Kondepudi Suresh, Huang Lixiao, Gopalan Nakul
conference: "Arxiv"
year: 2024
bibkey: gu2024continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03166"}
tags: ['Agentic', 'Efficiency And Optimization', 'Ethics And Bias', 'Fine Tuning', 'Reinforcement Learning', 'Tools']
---
Continual and interactive robot learning is a challenging problem as the robot is present with human users who expect the robot to learn novel skills to solve novel tasks perpetually with sample efficiency. In this work we present a framework for robots to query and learn visuo45;motor robot skills and task relevant information via natural language dialog interactions with human users. Previous approaches either focus on improving the performance of instruction following agents or passively learn novel skills or concepts. Instead we used dialog combined with a language45;skill grounding embedding to query or confirm skills and/or tasks requested by a user. To achieve this goal we developed and integrated three different components for our agent. Firstly we propose a novel visual45;motor control policy ACT with Low Rank Adaptation (ACT45;LoRA) which enables the existing SoTA ACT model to perform few45;shot continual learning. Secondly we develop an alignment model that projects demonstrations across skill embodiments into a shared embedding allowing us to know when to ask questions and/or demonstrations from users. Finally we integrated an existing LLM to interact with a human user to perform grounded interactive continual skill learning to solve a task. Our ACT45;LoRA model learns novel fine45;tuned skills with a 10037; accuracy when trained with only five demonstrations for a novel skill while still maintaining a 74.7537; accuracy on pre45;trained skills in the RLBench dataset where other models fall significantly short. We also performed a human45;subjects study with 8 subjects to demonstrate the continual learning capabilities of our combined framework. We achieve a success rate of 7537; in the task of sandwich making with the real robot learning from participant data demonstrating that robots can learn novel skills or task knowledge from dialogue with non45;expert users using our approach.
