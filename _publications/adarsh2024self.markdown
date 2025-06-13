---
layout: publication
title: 'Siked: Self-guided Iterative Knowledge Distillation For Mathematical Reasoning'
authors: Shivam Adarsh, Kumar Shridhar, Caglar Gulcehre, Nicholas Monath, Mrinmaya Sachan
conference: "Arxiv"
year: 2024
bibkey: adarsh2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18574"}
  - {name: "Code", url: "https://github.com/kumar-shridhar/SIKeD"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Distillation', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Large Language Models (LLMs) can transfer their reasoning skills to smaller
models by teaching them to generate the intermediate reasoning process required
to solve multistep reasoning tasks. While LLMs can accurately solve reasoning
tasks through a variety of strategies, even without fine-tuning, smaller models
are not expressive enough to fit the LLMs distribution on all strategies when
distilled and tend to prioritize one strategy over the others. This reliance on
one strategy poses a challenge for smaller models when attempting to solve
reasoning tasks that may be difficult with their preferred strategy. To address
this, we propose a distillation method SIKeD (Self-guided Iterative Knowledge
Distillation for mathematical reasoning), where the LLM teaches the smaller
model to approach a task using different strategies and the smaller model uses
its self-generated on-policy outputs to choose the most suitable strategy for
the given task. The training continues in a self-guided iterative manner, where
for each training iteration, a decision is made on how to combine the LLM data
with the self-generated outputs. Unlike traditional distillation methods, SIKeD
allows the smaller model to learn which strategy is suitable for a given task
while continuously learning to solve a task using different strategies. Our
experiments on various mathematical reasoning datasets show that SIKeD
significantly outperforms traditional distillation techniques across smaller
models of different sizes. Our code is available at:
https://github.com/kumar-shridhar/SIKeD
