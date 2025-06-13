---
layout: publication
title: 'Group Preference Alignment: Customized LLM Response Generation From In-situ Conversations'
authors: Ishani Mondal, Jack W. Stokes, Sujay Kumar Jauhar, Longqi Yang, Mengting Wan, Xiaofeng Xu, Xia Song, Jennifer Neville
conference: "Arxiv"
year: 2025
bibkey: mondal2025group
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.08035'}
tags: ['RAG', 'Training Techniques', 'Tools', 'Prompting', 'Reinforcement Learning']
---
LLMs often fail to meet the specialized needs of distinct user groups due to
their one-size-fits-all training paradigm \cite\{lucy-etal-2024-one\} and there
is limited research on what personalization aspects each group expect. To
address these limitations, we propose a group-aware personalization framework,
Group Preference Alignment (GPA), that identifies context-specific variations
in conversational preferences across user groups and then steers LLMs to
address those preferences. Our approach consists of two steps: (1) Group-Aware
Preference Extraction, where maximally divergent user-group preferences are
extracted from real-world conversation logs and distilled into interpretable
rubrics, and (2) Tailored Response Generation, which leverages these rubrics
through two methods: a) Context-Tuned Inference (GAP-CT), that dynamically
adjusts responses via context-dependent prompt instructions, and b)
Rubric-Finetuning Inference (GPA-FT), which uses the rubrics to generate
contrastive synthetic data for personalization of group-specific models via
alignment. Experiments demonstrate that our framework significantly improves
alignment of the output with respect to user preferences and outperforms
baseline methods, while maintaining robust performance on standard benchmarks.
