---
layout: publication
title: Data Contamination Through The Lens Of Time
authors: Roberts Manley, Thakur Himanshu, Herlihy Christine, White Colin, Dooley Samuel
conference: "Arxiv"
year: 2023
bibkey: roberts2023data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.10628"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Recent claims about the impressive abilities of large language models (LLMs) are often supported by evaluating publicly available benchmarks. Since LLMs train on wide swaths of the internet this practice raises concerns of data contamination i.e. evaluating on examples that are explicitly or implicitly included in the training data. Data contamination remains notoriously challenging to measure and mitigate even with partial attempts like controlled experimentation of training data canary strings or embedding similarities. In this work we conduct the first thorough longitudinal analysis of data contamination in LLMs by using the natural experiment of training cutoffs in GPT models to look at benchmarks released over time. Specifically we consider two code/mathematical problem45;solving datasets Codeforces and Project Euler and find statistically significant trends among LLM pass rate vs. GitHub popularity and release date that provide strong evidence of contamination. By open45;sourcing our dataset raw results and evaluation framework our work paves the way for rigorous analyses of data contamination in modern models. We conclude with a discussion of best practices and future steps for publicly releasing benchmarks in the age of LLMs that train on webscale data.
