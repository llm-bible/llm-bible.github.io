---
layout: publication
title: Length-controlled Alpacaeval A Simple Way To Debias Automatic Evaluators
authors: Dubois Yann, Galambosi Balázs, Liang Percy, Hashimoto Tatsunori B.
conference: "Arxiv"
year: 2024
bibkey: dubois2024length
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04475"}
  - {name: "Code", url: "https://tatsu-lab.github.io/alpaca\_eval/"}
tags: ['Ethics And Bias', 'Has Code', 'Security', 'Tools']
---
LLM-based auto-annotators have become a key component of the LLM development process due to their cost-effectiveness and scalability compared to human-based evaluation. However these auto-annotators can introduce complex biases that are hard to remove. Even simple known confounders such as preference for longer outputs remain in existing automated evaluation metrics. We propose a simple regression analysis approach for controlling biases in auto-evaluations. As a real case study we focus on reducing the length bias of AlpacaEval a fast and affordable benchmark for chat LLMs that uses LLMs to estimate response quality. Despite being highly correlated with human preferences AlpacaEval is known to favor models that generate longer outputs. We introduce a length-controlled AlpacaEval that aims to answer the counterfactual question What would the preference be if the models and baselines output had the same length. To achieve this we first fit a generalized linear model to predict the biased output of interest (auto-annotator preferences) based on the mediators we want to control for (length difference) and other relevant features. We then obtain length-controlled preferences by predicting preferences while conditioning the GLM with a zero difference in lengths. Length-controlling not only improves the robustness of the metric to manipulations in model verbosity we also find that it increases the Spearman correlation with LMSYS Chatbot Arena from 0.94 to 0.98. We release the code and leaderboard at https://tatsu-lab.github.io/alpaca\_eval/ .
