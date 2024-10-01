---
layout: publication
title: 'LBC: Language-based-classifier For Out-of-variable Generalization'
authors: Noh Kangjun, Seong Baekryun, Byun Hoyoon, Choi Youngjun, Song Sungjin, Song Kyungwoo
conference: "Arxiv"
year: 2024
bibkey: noh2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.10923"}
  - {name: "Code", url: "https://github.com/sksmssh/LBCforOOVGen"}
tags: ['Applications', 'Has Code', 'Training Techniques']
---
'Large Language Models (LLMs) have great success in natural language processing tasks such as response generation. However, their use in tabular data has been limited due to their inferior performance compared to traditional machine learning models (TMLs) such as XGBoost. We find that the pre-trained knowledge of LLMs enables them to interpret new variables that appear in a test without additional training, a capability central to the concept of Out-of-Variable (OOV). From the findings, we propose a Language-Based-Classifier (LBC), a classifier that maximizes the benefits of LLMs to outperform TMLs on OOV tasks. LBC employs three key methodological strategies: 1) Categorical changes to adjust data to better fit the model''s understanding, 2) Advanced order and indicator to enhance data representation to the model, and 3) Using verbalizer to map logit scores to classes during inference to generate model predictions. These strategies, combined with the pre-trained knowledge of LBC, emphasize the model''s ability to effectively handle OOV tasks. We empirically and theoretically validate the superiority of LBC. LBC is the first study to apply an LLM-based model to OOV tasks. The source code is at https://github.com/sksmssh/LBCforOOVGen'
