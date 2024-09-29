---
layout: publication
title: Human Choice Prediction In Language-based Persuasion Games&#58; Simulation-based Off-policy Evaluation
authors: Shapira Eilam, Apel Reut, Tennenholtz Moshe, Reichart Roi
conference: "Arxiv"
year: 2023
bibkey: shapira2023human
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.10361"}
  - {name: "Code", url: "https://github.com/eilamshapira/HumanChoicePrediction"}
tags: ['Agentic', 'Has Code', 'Tools', 'Training Techniques']
---
Recent advances in Large Language Models (LLMs) have spurred interest in designing LLM-based agents for tasks that involve interaction with human and artificial agents. This paper addresses a key aspect in the design of such agents Predicting human decision in off-policy evaluation (OPE) focusing on language-based persuasion games where the agents goal is to influence its partners decisions through verbal messages. Using a dedicated application we collected a dataset of 87K decisions from humans playing a repeated decision-making game with artificial agents. Our approach involves training a model on human interactions with one agents subset to predict decisions when interacting with another. To enhance off-policy performance we propose a simulation technique involving interactions across the entire agent space and simulated decision makers. Our learning strategy yields significant OPE gains e.g. improving prediction accuracy in the top 1537; challenging cases by 7.137;. Our code and the large dataset we collected and generated are submitted as supplementary material and publicly available in our GitHub repository https://github.com/eilamshapira/HumanChoicePrediction"
