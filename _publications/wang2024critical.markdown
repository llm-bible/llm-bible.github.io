---
layout: publication
title: 'CPL: Critical Plan Step Learning Boosts LLM Generalization In Reasoning Tasks'
authors: Tianlong Wang, Junzhe Chen, Xueting Han, Jing Bai
conference: "Arxiv"
year: 2024
bibkey: wang2024critical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.08642"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning']
---
Post-training, particularly reinforcement learning (RL) using
self-play-generated data, has become a new learning paradigm for large language
models (LLMs). However, scaling RL to develop a general reasoner remains a
research challenge, as existing methods focus on task-specific reasoning
without adequately addressing generalization across a broader range of tasks.
Moreover, unlike traditional RL with limited action space, LLMs operate in an
infinite space, making it crucial to search for valuable and diverse strategies
to solve problems effectively. To address this, we propose searching within the
action space on high-level abstract plans to enhance model generalization and
introduce Critical Plan Step Learning (CPL), comprising: 1) searching on plan,
using Monte Carlo Tree Search (MCTS) to explore diverse plan steps in
multi-step reasoning tasks, and 2) learning critical plan steps through
Step-level Advantage Preference Optimization (Step-APO), which integrates
advantage estimates for step preference obtained via MCTS into Direct
Preference Optimization (DPO). This combination helps the model effectively
learn critical plan steps, enhancing both reasoning capabilities and
generalization. Experimental results demonstrate that our method, trained
exclusively on GSM8K and MATH, not only significantly improves performance on
GSM8K (+10.5%) and MATH (+6.5%), but also enhances out-of-domain reasoning
benchmarks, such as HumanEval (+12.2%), GPQA (+8.6%), ARC-C (+4.0%), MMLU-STEM
(+2.2%), and BBH (+1.8%).
