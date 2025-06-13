---
layout: publication
title: 'Explore The Reasoning Capability Of Llms In The Chess Testbed'
authors: Shu Wang, Lei Ji, Renxi Wang, Wenxiao Zhao, Haokun Liu, Yifan Hou, Ying Nian Wu
conference: "Arxiv"
year: 2024
bibkey: wang2024explore
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.06655"}
tags: ['Model Architecture', 'GPT', 'Interpretability and Explainability']
---
Reasoning is a central capability of human intelligence. In recent years,
with the advent of large-scale datasets, pretrained large language models have
emerged with new capabilities, including reasoning. However, these models still
struggle with long-term, complex reasoning tasks, such as playing chess. Based
on the observation that expert chess players employ a dual approach combining
long-term strategic play with short-term tactical play along with language
explanation, we propose improving the reasoning capability of large language
models in chess by integrating annotated strategy and tactic. Specifically, we
collect a dataset named MATE, which consists of 1 million chess positions with
candidate moves annotated by chess experts for strategy and tactics. We
finetune the LLaMA-3-8B model and compare it against state-of-the-art
commercial language models in the task of selecting better chess moves. Our
experiments show that our models perform better than GPT, Claude, and Gemini
models. We find that language explanations can enhance the reasoning capability
of large language models.
