---
layout: publication
title: 'Rewarding Graph Reasoning Process Makes Llms More Generalized Reasoners'
authors: Miao Peng, Nuo Chen, Zongrui Suo, Jia Li
conference: "Arxiv"
year: 2025
bibkey: peng2025rewarding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00845"}
tags: ['Agentic', 'Efficiency and Optimization', 'Reinforcement Learning']
---
Despite significant advancements in Large Language Models (LLMs), developing
advanced reasoning capabilities in LLMs remains a key challenge. Process Reward
Models (PRMs) have demonstrated exceptional promise in enhancing reasoning by
providing step-wise feedback, particularly in the context of mathematical
reasoning. However, their application to broader reasoning domains remains
understudied, largely due to the high costs associated with manually creating
step-level supervision. In this work, we explore the potential of PRMs in graph
reasoning problems - a domain that demands sophisticated multi-step reasoning
and offers opportunities for automated step-level data generation using
established graph algorithms. We introduce GraphSILO, the largest dataset for
graph reasoning problems with fine-grained step-wise labels, built using
automated Task-oriented Trajectories and Monte Carlo Tree Search (MCTS) to
generate detailed reasoning steps with step-wise labels. Building upon this
dataset, we train GraphPRM, the first PRM designed for graph reasoning
problems, and evaluate its effectiveness in two key settings: inference-time
scaling and reinforcement learning via Direct Preference Optimization (DPO).
Experimental results show that GraphPRM significantly improves LLM performance
across 13 graph reasoning tasks, delivering a 9% gain for Qwen2.5-7B and
demonstrating transferability to new graph reasoning datasets and new reasoning
domains like mathematical problem-solving. Notably, GraphPRM enhances LLM
performance on GSM8K and Math500, underscoring the cross-domain applicability
of graph-based reasoning rewards. Our findings highlight the potential of PRMs
in advancing reasoning across diverse domains, paving the way for more
versatile and effective LLMs.
