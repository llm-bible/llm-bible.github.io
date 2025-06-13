---
layout: publication
title: 'Judging The Judges: A Systematic Study Of Position Bias In Llm-as-a-judge'
authors: Lin Shi, Chiyu Ma, Wenhua Liang, Xingjian Diao, Weicheng Ma, Soroush Vosoughi
conference: "Arxiv"
year: 2024
bibkey: shi2024judging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.07791'}
tags: ['Fairness', 'Fine-Tuning', 'Prompting', 'Bias Mitigation', 'Reinforcement Learning', 'Ethics and Bias']
---
LLM-as-a-Judge has emerged as a promising alternative to human evaluators
across various tasks, yet inherent biases - particularly position bias, the
tendency to favor solutions based on their position within the prompt -
compromise its reliability. This exploratory study evaluates position bias in
LLM judges across pairwise and list-wise comparison settings, introducing three
metrics: repetition stability, position consistency, and preference fairness.
Our experiments, involving 15 LLM judges across MTBench and DevBench with 22
tasks and approximately 40 solution-generating models, result in over 150,000
evaluation instances. We identify Judge-Level, Candidate-Level, and Task-Level
factors contributing to bias. The findings confirm that position bias is not
due to random chance and varies significantly across judges and tasks. While
position bias is weakly influenced by the length of prompt components, it is
strongly affected by the quality gap between solutions. Our agreement and
disagreement analysis among judges further provides insights into the
distribution of judging difficulty across the dataset, and highlights the
potential for dataset modifications.
