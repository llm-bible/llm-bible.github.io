---
layout: publication
title: 'TEGEE: Task Definition Guided Expert Ensembling For Generalizable And Few-shot Learning'
authors: Xingwei Qu, Yiming Liang, Yucheng Wang, Tianyu Zheng, Tommy Yue, Xingyuan Bu, Lei Ma, Stephen W. Huang, Jiajun Zhang, Yinan Shi, Chenghua Lin, Jie Fu, Ge Zhang
conference: "Arxiv"
year: 2024
bibkey: qu2024task
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.04233'}
tags: ['Reinforcement Learning', 'Few-Shot', 'RAG', 'Tools']
---
Large Language Models (LLMs) exhibit the ability to perform in-context
learning (ICL), where they acquire new tasks directly from examples provided in
demonstrations. This process is thought to operate through an implicit task
selection mechanism that involves extracting and processing task definitions
from these demonstrations. However, critical questions remain: Which is more
essential -- task extraction or definition? And how can these capabilities be
further improved? To address these questions, we propose \textbf\{TEGEE\} (Task
Definition Guided Expert Ensembling), a method that explicitly extracts task
definitions and generates responses based on specific tasks. Our framework
employs a dual 3B model approach, with each model assigned a distinct role: one
focuses on task definition extraction, while the other handles learning from
demonstrations. This modular approach supports the hypothesis that extracting
task definitions is more vital than processing the task itself. Empirical
evaluations show that TEGEE performs comparably to the larger LLaMA2-13B model.
By leveraging a modular design, our approach extends traditional ICL from
few-shot to many-shot learning, supporting an unlimited number of
demonstrations and enhancing continual learning capabilities.
