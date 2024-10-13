---
layout: publication
title: 'End-to-end Neuro-symbolic Reinforcement Learning With Textual Explanations'
authors: Luo Lirui, Zhang Guoxi, Xu Hongming, Yang Yaodong, Fang Cong, Li Qing
conference: "Arxiv"
year: 2024
bibkey: luo2024end
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12451"}
tags: ['Agentic', 'Efficiency And Optimization', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Neuro-symbolic reinforcement learning (NS-RL) has emerged as a promising
paradigm for explainable decision-making, characterized by the interpretability
of symbolic policies. NS-RL entails structured state representations for tasks
with visual observations, but previous methods cannot refine the structured
states with rewards due to a lack of efficiency. Accessibility also remains an
issue, as extensive domain knowledge is required to interpret symbolic
policies. In this paper, we present a neuro-symbolic framework for jointly
learning structured states and symbolic policies, whose key idea is to distill
the vision foundation model into an efficient perception module and refine it
during policy learning. Moreover, we design a pipeline to prompt GPT-4 to
generate textual explanations for the learned policies and decisions,
significantly reducing users' cognitive load to understand the symbolic
policies. We verify the efficacy of our approach on nine Atari tasks and
present GPT-generated explanations for policies and decisions.
