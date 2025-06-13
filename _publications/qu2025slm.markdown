---
layout: publication
title: 'SHARE: An Slm-based Hierarchical Action Correction Assistant For Text-to-sql'
authors: Ge Qu, Jinyang Li, Bowen Qin, Xiaolong Li, Nan Huo, Chenhao Ma, Reynold Cheng
conference: "Arxiv"
year: 2025
bibkey: qu2025slm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.00391'}
tags: ['Reinforcement Learning', 'Training Techniques', 'Applications']
---
Current self-correction approaches in text-to-SQL face two critical limitations: 1) Conventional self-correction methods rely on recursive self-calls of LLMs, resulting in multiplicative computational overhead, and 2) LLMs struggle to implement effective error detection and correction for declarative SQL queries, as they fail to demonstrate the underlying reasoning path. In this work, we propose SHARE, an SLM-based Hierarchical Action corREction assistant that enables LLMs to perform more precise error localization and efficient correction. SHARE orchestrates three specialized Small Language Models (SLMs) in a sequential pipeline, where it first transforms declarative SQL queries into stepwise action trajectories that reveal underlying reasoning, followed by a two-phase granular refinement. We further propose a novel hierarchical self-evolution strategy for data-efficient training. Experimental results demonstrate that SHARE effectively enhances self-correction capabilities while proving robust across various LLMs. Furthermore, our comprehensive analysis shows that SHARE maintains strong performance even in low-resource training settings, which is particularly valuable for text-to-SQL applications with data privacy constraints.
