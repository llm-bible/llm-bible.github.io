---
layout: publication
title: 'Language Models Can Infer Action Semantics For Symbolic Planners From Environment Feedback'
authors: Wang Zhu, Ishika Singh, Robin Jia, Jesse Thomason
conference: "Arxiv"
year: 2024
bibkey: zhu2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02791"}
tags: ['RAG']
---
Symbolic planners can discover a sequence of actions from initial to goal
states given expert-defined, domain-specific logical action semantics. Large
Language Models (LLMs) can directly generate such sequences, but limitations in
reasoning and state-tracking often result in plans that are insufficient or
unexecutable. We propose Predicting Semantics of Actions with Language Models
(PSALM), which automatically learns action semantics by leveraging the
strengths of both symbolic planners and LLMs. PSALM repeatedly proposes and
executes plans, using the LLM to partially generate plans and to infer
domain-specific action semantics based on execution outcomes. PSALM maintains a
belief over possible action semantics that is iteratively updated until a goal
state is reached. Experiments on 7 environments show that when learning just
from one goal, PSALM boosts plan success rate from 36.4% (on Claude-3.5) to
100%, and explores the environment more efficiently than prior work to infer
ground truth domain action semantics.
