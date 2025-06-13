---
layout: publication
title: 'Potential And Limitations Of Llms In Capturing Structured Semantics: A Case Study On SRL'
authors: Ning Cheng, Zhaohui Yan, Ziming Wang, Zhijie Li, Jiaming Yu, Zilong Zheng, Kewei Tu, Jinan Xu, Wenjuan Han
conference: "Arxiv"
year: 2024
bibkey: cheng2024potential
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.06410"}
tags: ['Few-Shot', 'Reinforcement Learning', 'Ethics and Bias', 'Interpretability and Explainability', 'Prompting']
---
Large Language Models (LLMs) play a crucial role in capturing structured
semantics to enhance language understanding, improve interpretability, and
reduce bias. Nevertheless, an ongoing controversy exists over the extent to
which LLMs can grasp structured semantics. To assess this, we propose using
Semantic Role Labeling (SRL) as a fundamental task to explore LLMs' ability to
extract structured semantics. In our assessment, we employ the prompting
approach, which leads to the creation of our few-shot SRL parser, called
PromptSRL. PromptSRL enables LLMs to map natural languages to explicit semantic
structures, which provides an interpretable window into the properties of LLMs.
We find interesting potential: LLMs can indeed capture semantic structures, and
scaling-up doesn't always mirror potential. Additionally, limitations of LLMs
are observed in C-arguments, etc. Lastly, we are surprised to discover that
significant overlap in the errors is made by both LLMs and untrained humans,
accounting for almost 30% of all errors.
