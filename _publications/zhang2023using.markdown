---
layout: publication
title: 'Using Large Language Models For Hyperparameter Optimization'
authors: Michael R. Zhang, Nishkrit Desai, Juhan Bae, Jonathan Lorraine, Jimmy Ba
conference: "Arxiv"
year: 2023
bibkey: zhang2023using
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.04528'}
tags: ['Prompting', 'Efficiency and Optimization']
---
This paper explores the use of foundational large language models (LLMs) in
hyperparameter optimization (HPO). Hyperparameters are critical in determining
the effectiveness of machine learning models, yet their optimization often
relies on manual approaches in limited-budget settings. By prompting LLMs with
dataset and model descriptions, we develop a methodology where LLMs suggest
hyperparameter configurations, which are iteratively refined based on model
performance. Our empirical evaluations on standard benchmarks reveal that
within constrained search budgets, LLMs can match or outperform traditional HPO
methods like Bayesian optimization across different models on standard
benchmarks. Furthermore, we propose to treat the code specifying our model as a
hyperparameter, which the LLM outputs and affords greater flexibility than
existing HPO approaches.
