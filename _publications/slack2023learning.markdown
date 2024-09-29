---
layout: publication
title: TABLET Learning From Instructions For Tabular Data
authors: Slack Dylan, Singh Sameer
conference: "Arxiv"
year: 2023
bibkey: slack2023learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.13188"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Acquiring high45;quality data is often a significant challenge in training machine learning (ML) models for tabular prediction particularly in privacy45;sensitive and costly domains like medicine and finance. Providing natural language instructions to large language models (LLMs) offers an alternative solution. However it is unclear how effectively instructions leverage the knowledge in LLMs for solving tabular prediction problems. To address this gap we introduce TABLET a benchmark of 20 diverse tabular datasets annotated with instructions that vary in their phrasing granularity and technicality. Additionally TABLET includes the instructions logic and structured modifications to the instructions. We find in45;context instructions increase zero45;shot F1 performance for Flan45;T5 11b by 4437; on average and 1337; for ChatGPT on TABLET. Also we explore the limitations of using LLMs for tabular prediction in our benchmark by evaluating instruction faithfulness. We find LLMs often ignore instructions and fail to predict specific instances correctly even with examples. Our analysis on TABLET shows that while instructions help LLM performance learning from instructions for tabular data requires new capabilities.
