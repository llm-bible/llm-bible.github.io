---
layout: publication
title: Open45;llm45;leaderboard From Multi45;choice To Open45;style Questions For Llms Evaluation Benchmark And Arena
authors: Myrzakhan Aidar, Bsharat Sondos Mahmoud, Shen Zhiqiang
conference: "Arxiv"
year: 2024
bibkey: myrzakhan2024open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07545"}
  - {name: "Code", url: "https://github.com/VILA&#45;Lab/Open&#45;LLM&#45;Leaderboard"}
tags: ['Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'Tools']
---
Multiple45;choice questions (MCQ) are frequently used to assess large language models (LLMs). Typically an LLM is given a question and selects the answer deemed most probable after adjustments for factors like length. Unfortunately LLMs may inherently favor certain answer choice IDs such as A/B/C/D due to inherent biases of priori unbalanced probabilities influencing the prediction of answers based on these IDs. Previous research has introduced methods to reduce this selection bias by simply permutating options on a few test samples and applying to new ones. Another problem of MCQ is the lottery ticket choice by random guessing. The LLM does not learn particular knowledge but the option is guessed correctly. This situation is especially serious for those small45;scale LLMs. To address them a more thorough approach involves shifting from MCQ to open45;style questions which can fundamentally eliminate selection bias and random guessing issues. However transitioning causes its own set of challenges in (1) identifying suitable open45;style questions and (2) validating the correctness of LLM open45;style responses against human45;annotated ground45;truths. This work aims to tackle these significant difficulties and establish a new LLM evaluation benchmark through entirely open45;style questions. Consequently we introduce the Open45;LLM45;Leaderboard to track various LLMs performance and reflect true capability of them such as GPT45;4o/4/3.5 Claude 3 Gemini etc. Our code and dataset are available at https://github.com/VILA&#45;Lab/Open&#45;LLM&#45;Leaderboard.
