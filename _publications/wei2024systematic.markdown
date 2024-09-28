---
layout: publication
title: Systematic Evaluation of LLM-as-a-Judge in LLM Alignment Tasks Explainable Metrics and Diverse Prompt Templates
authors: Wei Hui, He Shenghua, Xia Tian, Wong Andy, Lin Jingyang, Han Mei
conference: "Arxiv"
year: 2024
bibkey: wei2024systematic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.13006"}
tags: ['ARXIV', 'Applications', 'Ethics And Bias', 'GPT', 'Interpretability', 'Interpretability And Interpretability', 'LLM', 'Prompting', 'Reinforcement Learning', 'Tools']
---
Alignment approaches such as RLHF and DPO are actively investigated to align large language models (LLMs) with human preferences. Commercial large language models (LLMs) like GPT-4 have been recently employed to evaluate and compare different LLM alignment approaches. These models act as surrogates for human evaluators due to their promising abilities to approximate human preferences with remarkably faster feedback and lower costs. This methodology is referred to as LLM-as-a-judge. However concerns regarding its reliability have emerged attributed to LLM judges biases and inconsistent decision-making. Previous research has sought to develop robust evaluation frameworks for assessing the reliability of LLM judges and their alignment with human preferences. However the employed evaluation metrics often lack adequate explainability and fail to address the internal inconsistency of LLMs. Additionally existing studies inadequately explore the impact of various prompt templates when applying LLM-as-a-judge methods which leads to potentially inconsistent comparisons between different alignment algorithms. In this work we systematically evaluate LLM judges on alignment tasks (e.g. summarization) by defining evaluation metrics with improved theoretical interpretability and disentangling reliability metrics with LLM internal inconsistency. We develop a framework to evaluate compare and visualize the reliability and alignment of LLM judges to provide informative observations that help choose LLM judges for alignment tasks. Our results indicate a significant impact of prompt templates on LLM judge performance as well as a mediocre alignment level between the tested LLM judges and human evaluators.
