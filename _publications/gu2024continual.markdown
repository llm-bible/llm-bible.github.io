---
layout: publication
title: 'Continual Skill And Task Learning Via Dialogue'
authors: Gu Weiwei, Kondepudi Suresh, Huang Lixiao, Gopalan Nakul
conference: "Arxiv"
year: 2024
bibkey: gu2024continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.03166"}
tags: ['Agentic', 'Efficiency And Optimization', 'Few Shot', 'Fine Tuning', 'Reinforcement Learning', 'Tools', 'Uncategorized']
---
Continual and interactive robot learning is a challenging problem as the
robot is present with human users who expect the robot to learn novel skills to
solve novel tasks perpetually with sample efficiency. In this work we present a
framework for robots to query and learn visuo-motor robot skills and task
relevant information via natural language dialog interactions with human users.
Previous approaches either focus on improving the performance of instruction
following agents, or passively learn novel skills or concepts. Instead, we used
dialog combined with a language-skill grounding embedding to query or confirm
skills and/or tasks requested by a user. To achieve this goal, we developed and
integrated three different components for our agent. Firstly, we propose a
novel visual-motor control policy ACT with Low Rank Adaptation (ACT-LoRA),
which enables the existing SoTA ACT model to perform few-shot continual
learning. Secondly, we develop an alignment model that projects demonstrations
across skill embodiments into a shared embedding allowing us to know when to
ask questions and/or demonstrations from users. Finally, we integrated an
existing LLM to interact with a human user to perform grounded interactive
continual skill learning to solve a task. Our ACT-LoRA model learns novel
fine-tuned skills with a 100% accuracy when trained with only five
demonstrations for a novel skill while still maintaining a 74.75% accuracy on
pre-trained skills in the RLBench dataset where other models fall significantly
short. We also performed a human-subjects study with 8 subjects to demonstrate
the continual learning capabilities of our combined framework. We achieve a
success rate of 75% in the task of sandwich making with the real robot learning
from participant data demonstrating that robots can learn novel skills or task
knowledge from dialogue with non-expert users using our approach.
