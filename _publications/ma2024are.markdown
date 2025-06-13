---
layout: publication
title: 'Are Large Language Models Good Prompt Optimizers?'
authors: Ruotian Ma, Xiaolei Wang, Xin Zhou, Jian Li, Nan Du, Tao Gui, Qi Zhang, Xuanjing Huang
conference: "Arxiv"
year: 2024
bibkey: ma2024are
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.02101"}
tags: ['Efficiency and Optimization', 'Survey Paper', 'Ethics and Bias', 'Reinforcement Learning', 'Prompting']
---
LLM-based Automatic Prompt Optimization, which typically utilizes LLMs as
Prompt Optimizers to self-reflect and refine prompts, has shown promising
performance in recent studies. Despite the success, the underlying mechanism of
this approach remains unexplored, and the true effectiveness of LLMs as Prompt
Optimizers requires further validation. In this work, we conducted a
comprehensive study to uncover the actual mechanism of LLM-based Prompt
Optimization. Our findings reveal that the LLM optimizers struggle to identify
the true causes of errors during reflection, tending to be biased by their own
prior knowledge rather than genuinely reflecting on the errors. Furthermore,
even when the reflection is semantically valid, the LLM optimizers often fail
to generate appropriate prompts for the target models with a single prompt
refinement step, partly due to the unpredictable behaviors of the target
models. Based on the observations, we introduce a new "Automatic Behavior
Optimization" paradigm, which directly optimizes the target model's behavior in
a more controllable manner. We hope our study can inspire new directions for
automatic prompt optimization development.
