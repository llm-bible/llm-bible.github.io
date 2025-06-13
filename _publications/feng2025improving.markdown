---
layout: publication
title: 'Improving Retrospective Language Agents Via Joint Policy Gradient Optimization'
authors: Xueyang Feng, Bo Lan, Quanyu Dai, Lei Wang, Jiakai Tang, Xu Chen, Zhenhua Dong, Ji-rong Wen
conference: "Arxiv"
year: 2025
bibkey: feng2025improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.01490"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Agent', 'Pretraining Methods', 'Prompting']
---
In recent research advancements within the community, large language models
(LLMs) have sparked great interest in creating autonomous agents. However,
current prompt-based agents often heavily rely on large-scale LLMs. Meanwhile,
although fine-tuning methods significantly enhance the capabilities of smaller
LLMs, the fine-tuned agents often lack the potential for self-reflection and
self-improvement. To address these challenges, we introduce a novel agent
framework named RetroAct, which is a framework that jointly optimizes both
task-planning and self-reflective evolution capabilities in language agents.
Specifically, we develop a two-stage joint optimization process that integrates
imitation learning and reinforcement learning, and design an off-policy joint
policy gradient optimization algorithm with imitation learning regularization
to enhance the data efficiency and training stability in agent tasks. RetroAct
significantly improves the performance of open-source models, reduces
dependency on closed-source LLMs, and enables fine-tuned agents to learn and
evolve continuously. We conduct extensive experiments across various testing
environments, demonstrating RetroAct has substantial improvements in task
performance and decision-making processes.
