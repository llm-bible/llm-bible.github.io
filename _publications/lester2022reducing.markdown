---
layout: publication
title: 'Reducing Retraining By Recycling Parameter-efficient Prompts'
authors: Brian Lester, Joshua Yurtsever, Siamak Shakeri, Noah Constant
conference: "Arxiv"
year: 2022
bibkey: lester2022reducing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2208.05577'}
tags: ['Prompting', 'Training Techniques']
---
Parameter-efficient methods are able to use a single frozen pre-trained large
language model (LLM) to perform many tasks by learning task-specific soft
prompts that modulate model behavior when concatenated to the input text.
However, these learned prompts are tightly coupled to a given frozen model --
if the model is updated, corresponding new prompts need to be obtained. In this
work, we propose and investigate several approaches to "Prompt Recycling'"
where a prompt trained on a source model is transformed to work with the new
target model. Our methods do not rely on supervised pairs of prompts,
task-specific data, or training updates with the target model, which would be
just as costly as re-tuning prompts with the target model from scratch. We show
that recycling between models is possible (our best settings are able to
successfully recycle \\(88.9%\\) of prompts, producing a prompt that out-performs
baselines), but significant performance headroom remains, requiring improved
recycling techniques.
