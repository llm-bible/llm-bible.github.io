---
layout: publication
title: 'S2LPP: Small-to-large Prompt Prediction Across Llms'
authors: Liang Cheng, Tianyi Li, Zhaowei Wang, Mark Steedman
conference: "Arxiv"
year: 2025
bibkey: cheng2025small
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.20097"}
tags: ['Prompting', 'Security', 'Applications']
---
The performance of pre-trained Large Language Models (LLMs) is often sensitive to nuances in prompt templates, requiring careful prompt engineering, adding costs in terms of computing and human effort. In this study, we present experiments encompassing multiple LLMs variants of varying sizes aimed at probing their preference with different prompts. Through experiments on Question Answering, we show prompt preference consistency across LLMs of different sizes. We also show that this consistency extends to other tasks, such as Natural Language Inference. Utilizing this consistency, we propose a method to use a smaller model to select effective prompt templates for a larger model. We show that our method substantially reduces the cost of prompt engineering while consistently matching performance with optimal prompts among candidates. More importantly, our experiment shows the efficacy of our strategy across fourteen LLMs and its applicability to a broad range of NLP tasks, highlighting its robustness
