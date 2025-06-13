---
layout: publication
title: 'Human Choice Prediction In Language-based Persuasion Games: Simulation-based Off-policy Evaluation'
authors: Eilam Shapira, Omer Madmon, Reut Apel, Moshe Tennenholtz, Roi Reichart
conference: "Arxiv"
year: 2023
bibkey: shapira2023human
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.10361'}
  - {name: "Code", url: 'https://github.com/eilamshapira/HumanChoicePrediction'}
tags: ['Agentic', 'Has Code', 'Tools']
---
Recent advances in Large Language Models (LLMs) have spurred interest in
designing LLM-based agents for tasks that involve interaction with human and
artificial agents. This paper addresses a key aspect in the design of such
agents: predicting human decisions in off-policy evaluation (OPE). We focus on
language-based persuasion games, where an expert aims to influence the
decision-maker through verbal messages. In our OPE framework, the prediction
model is trained on human interaction data collected from encounters with one
set of expert agents, and its performance is evaluated on interactions with a
different set of experts. Using a dedicated application, we collected a dataset
of 87K decisions from humans playing a repeated decision-making game with
artificial agents. To enhance off-policy performance, we propose a simulation
technique involving interactions across the entire agent space and simulated
decision-makers. Our learning strategy yields significant OPE gains, e.g.,
improving prediction accuracy in the top 15% challenging cases by 7.1%. Our
code and the large dataset we collected and generated are submitted as
supplementary material and publicly available in our GitHub repository:
https://github.com/eilamshapira/HumanChoicePrediction
