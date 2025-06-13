---
layout: publication
title: 'On The Role Of Model Prior In Real-world Inductive Reasoning'
authors: Zhuo Liu, Ding Yu, Hangfeng He
conference: "Arxiv"
year: 2024
bibkey: liu2024role
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.13645"}
tags: ['Applications', 'Reinforcement Learning']
---
Large Language Models (LLMs) show impressive inductive reasoning
capabilities, enabling them to generate hypotheses that could generalize
effectively to new instances when guided by in-context demonstrations. However,
in real-world applications, LLMs' hypothesis generation is not solely
determined by these demonstrations but is significantly shaped by task-specific
model priors. Despite their critical influence, the distinct contributions of
model priors versus demonstrations to hypothesis generation have been
underexplored. This study bridges this gap by systematically evaluating three
inductive reasoning strategies across five real-world tasks with three LLMs.
Our empirical findings reveal that, hypothesis generation is primarily driven
by the model's inherent priors; removing demonstrations results in minimal loss
of hypothesis quality and downstream usage. Further analysis shows the result
is consistent across various label formats with different label configurations,
and prior is hard to override, even under flipped labeling. These insights
advance our understanding of the dynamics of hypothesis generation in LLMs and
highlight the potential for better utilizing model priors in real-world
inductive reasoning tasks.
