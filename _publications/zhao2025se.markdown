---
layout: publication
title: 'SE Arena: An Interactive Platform For Evaluating Foundation Models In Software Engineering'
authors: Zhimin Zhao
conference: "Arxiv"
year: 2025
bibkey: zhao2025se
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.01860'}
tags: ['Reinforcement Learning', 'Efficiency and Optimization', 'Applications', 'Tools']
---
Foundation models (FMs), particularly large language models (LLMs), have
shown significant promise in various software engineering (SE) tasks, including
code generation, debugging, and requirement refinement. Despite these advances,
existing evaluation frameworks are insufficient for assessing model performance
in iterative, context-rich workflows characteristic of SE activities. To
address this limitation, we introduce SE Arena, an interactive platform
designed to evaluate FMs in SE tasks. SE Arena provides a transparent,
open-source leaderboard, supports multi-round conversational workflows, and
enables end-to-end model comparisons. The platform introduces novel metrics,
including model consistency score that measures the consistency of model
outputs through self-play matches, and conversation efficiency index that
evaluates model performance while accounting for the number of interaction
rounds required to reach conclusions. Moreover, SE Arena incorporates a new
feature called RepoChat, which automatically injects repository-related context
(e.g., issues, commits, pull requests) into the conversation, further aligning
evaluations with real-world development processes. This paper outlines the
design and capabilities of SE Arena, emphasizing its potential to advance the
evaluation and practical application of FMs in software engineering.
