---
layout: publication
title: 'Unveiling The Mechanisms Of Explicit Cot Training: How Cot Enhances Reasoning Generalization'
authors: Xinhao Yao, Ruifeng Ren, Yun Liao, Yong Liu
conference: "Arxiv"
year: 2025
bibkey: yao2025unveiling
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.04667'}
tags: ['Reinforcement Learning', 'Security', 'Training Techniques']
---
The integration of explicit Chain-of-Thought (CoT) reasoning into training
large language models (LLMs) has advanced their reasoning capabilities, yet the
mechanisms by which CoT enhances generalization remain poorly understood. This
work investigates (1) \textit\{how\} CoT training reshapes internal model
representations and (2) \textit\{why\} it improves both in-distribution (ID) and
out-of-distribution (OOD) reasoning generalization. Through controlled
experiments and theoretical analysis, we derive the following key insights.
\textbf\{1)\} Structural Advantage: CoT training internalizes reasoning into a
two-stage generalizing circuit, where the number of stages corresponds to the
explicit reasoning steps during training. Notably, CoT-trained models resolve
intermediate results at shallower layers compared to non-CoT counterparts,
freeing up deeper layers to specialize in subsequent reasoning steps.
\textbf\{2)\} Theoretical Analysis: the information-theoretic generalization
bounds via distributional divergence can be decomposed into ID and OOD
components. While ID error diminishes with sufficient training regardless of
CoT, OOD error critically depends on CoT: Non-CoT training fails to generalize
to OOD samples due to unseen reasoning patterns, whereas CoT training achieves
near-perfect OOD generalization by mastering subtasks and reasoning
compositions during training. The identified mechanisms explain our
experimental results: CoT training accelerates convergence and enhances
generalization from ID to both ID and OOD scenarios while maintaining robust
performance even with tolerable noise. These findings are further validated on
complex real-world datasets. This paper offers valuable insights for designing
CoT strategies to enhance LLM reasoning robustness.
