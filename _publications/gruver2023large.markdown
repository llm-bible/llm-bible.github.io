---
layout: publication
title: Large Language Models Are Zero45;shot Time Series Forecasters
authors: Gruver Nate, Finzi Marc, Qiu Shikai, Wilson Andrew Gordon
conference: "Arxiv"
year: 2023
bibkey: gruver2023large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07820"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning']
---
By encoding time series as a string of numerical digits we can frame time series forecasting as next45;token prediction in text. Developing this approach we find that large language models (LLMs) such as GPT45;3 and LLaMA45;2 can surprisingly zero45;shot extrapolate time series at a level comparable to or exceeding the performance of purpose45;built time series models trained on the downstream tasks. To facilitate this performance we propose procedures for effectively tokenizing time series data and converting discrete distributions over tokens into highly flexible densities over continuous values. We argue the success of LLMs for time series stems from their ability to naturally represent multimodal distributions in conjunction with biases for simplicity and repetition which align with the salient features in many time series such as repeated seasonal trends. We also show how LLMs can naturally handle missing data without imputation through non45;numerical text accommodate textual side information and answer questions to help explain predictions. While we find that increasing model size generally improves performance on time series we show GPT45;4 can perform worse than GPT45;3 because of how it tokenizes numbers and poor uncertainty calibration which is likely the result of alignment interventions such as RLHF.
