---
layout: publication
title: 'See Or Recall: A Sanity Check For The Role Of Vision In Solving Visualization Question Answer Tasks With Multimodal Llms'
authors: Zhimin Li, Haichao Miao, Xinyuan Yan, Valerio Pascucci, Matthew Berger, Shusen Liu
conference: "Arxiv"
year: 2025
bibkey: li2025see
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.09809"}
tags: ['Multimodal Models', 'Tools', 'Reinforcement Learning', 'Ethics and Bias', 'Applications']
---
Recent developments in multimodal large language models (MLLM) have equipped
language models to reason about vision and language jointly. This permits MLLMs
to both perceive and answer questions about data visualization across a variety
of designs and tasks. Applying MLLMs to a broad range of visualization tasks
requires us to properly evaluate their capabilities, and the most common way to
conduct evaluation is through measuring a model's visualization reasoning
capability, analogous to how we would evaluate human understanding of
visualizations (e.g., visualization literacy). However, we found that in the
context of visualization question answering (VisQA), how an MLLM perceives and
reasons about visualizations can be fundamentally different from how humans
approach the same problem. During the evaluation, even without visualization,
the model could correctly answer a substantial portion of the visualization
test questions, regardless of whether any selection options were provided. We
hypothesize that the vast amount of knowledge encoded in the language model
permits factual recall that supersedes the need to seek information from the
visual signal. It raises concerns that the current VisQA evaluation may not
fully capture the models' visualization reasoning capabilities. To address
this, we propose a comprehensive sanity check framework that integrates a
rule-based decision tree and a sanity check table to disentangle the effects of
"seeing" (visual processing) and "recall" (reliance on prior knowledge). This
validates VisQA datasets for evaluation, highlighting where models are truly
"seeing", positively or negatively affected by the factual recall, or relying
on inductive biases for question answering. Our study underscores the need for
careful consideration in designing future visualization understanding studies
when utilizing MLLMs.
