---
layout: publication
title: 'Real-time Personalization For Llm-based Recommendation With Customized In-context Learning'
authors: Keqin Bao, Ming Yan, Yang Zhang, Jizhi Zhang, Wenjie Wang, Fuli Feng, Xiangnan He
conference: "Arxiv"
year: 2024
bibkey: bao2024real
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23136"}
  - {name: "Code", url: "https://github.com/ym689/rec_icl"}
tags: ['Training Techniques', 'Few-Shot', 'RAG', 'RecSys', 'Has Code', 'Prompting', 'In-Context Learning']
---
Frequently updating Large Language Model (LLM)-based recommender systems to
adapt to new user interests -- as done for traditional ones -- is impractical
due to high training costs, even with acceleration methods. This work explores
adapting to dynamic user interests without any model updates by leveraging
In-Context Learning (ICL), which allows LLMs to learn new tasks from few-shot
examples provided in the input. Using new-interest examples as the ICL few-shot
examples, LLMs may learn real-time interest directly, avoiding the need for
model updates. However, existing LLM-based recommenders often lose the
in-context learning ability during recommendation tuning, while the original
LLM's in-context learning lacks recommendation-specific focus. To address this,
we propose RecICL, which customizes recommendation-specific in-context learning
for real-time recommendations. RecICL organizes training examples in an
in-context learning format, ensuring that in-context learning ability is
preserved and aligned with the recommendation task during tuning.
  Extensive experiments demonstrate RecICL's effectiveness in delivering
real-time recommendations without requiring model updates. Our code is
available at https://github.com/ym689/rec_icl.
