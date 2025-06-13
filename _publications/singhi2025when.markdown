---
layout: publication
title: 'When To Solve, When To Verify: Compute-optimal Problem Solving And Generative Verification For LLM Reasoning'
authors: Nishad Singhi, Hritik Bansal, Arian Hosseini, Aditya Grover, Kai-wei Chang, Marcus Rohrbach, Anna Rohrbach
conference: "Arxiv"
year: 2025
bibkey: singhi2025when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.01005"}
  - {name: "Code", url: "https://github.com/nishadsinghi/sc-genrm-scaling"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Large-Scale Training', 'Has Code', 'Scaling Laws']
---
Scaling test-time compute has emerged as a key strategy for enhancing the
reasoning capabilities of large language models (LLMs), particularly in tasks
like mathematical problem-solving. A traditional approach, Self-Consistency
(SC), generates multiple solutions to a problem and selects the most common
answer via majority voting. Another common method involves scoring each
solution with a reward model (verifier) and choosing the best one. Recent
advancements in Generative Reward Models (GenRM) reframe verification as a
next-token prediction task, enabling inference-time scaling along a new axis.
Specifically, GenRM generates multiple verification chains-of-thought to score
each solution. Under a limited inference budget, this introduces a fundamental
trade-off: should you spend the budget on scaling solutions via SC or generate
fewer solutions and allocate compute to verification via GenRM? To address
this, we evaluate GenRM against SC under a fixed inference budget.
Interestingly, we find that SC is more compute-efficient than GenRM for most
practical inference budgets across diverse models and datasets. For instance,
GenRM first matches SC after consuming up to 8x the inference compute and
requires significantly more compute to outperform it. Furthermore, we derive
inference scaling laws for the GenRM paradigm, revealing that compute-optimal
inference favors scaling solution generation more aggressively than scaling the
number of verifications. Our work provides practical guidance on optimizing
test-time scaling by balancing solution generation and verification. The code
is available at https://github.com/nishadsinghi/sc-genrm-scaling.
