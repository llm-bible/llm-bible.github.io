---
layout: publication
title: Reindex-Then-Adapt Improving Large Language Models for Conversational Recommendation
authors: He Zhankui, Xie Zhouhang, Steck Harald, Liang Dawen, Jha Rahul, Kallus Nathan, Mcauley Julian
conference: "Arxiv"
year: 2024
bibkey: he2024reindex
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12119"}
tags: ['GPT', 'Pretraining Methods', 'Tools']
---
Large language models (LLMs) are revolutionizing conversational recommender systems by adeptly indexing item content understanding complex conversational contexts and generating relevant item titles. However controlling the distribution of recommended items remains a challenge. This leads to suboptimal performance due to the failure to capture rapidly changing data distributions such as item popularity on targeted conversational recommendation platforms. In conversational recommendation LLMs recommend items by generating the titles (as multiple tokens) autoregressively making it difficult to obtain and control the recommendations over all items. Thus we propose a Reindex-Then-Adapt (RTA) framework which converts multi-token item titles into single tokens within LLMs and then adjusts the probability distributions over these single-token item titles accordingly. The RTA framework marries the benefits of both LLMs and traditional recommender systems (RecSys) understanding complex queries as LLMs do; while efficiently controlling the recommended item distributions in conversational recommendations as traditional RecSys do. Our framework demonstrates improved accuracy metrics across three different conversational recommendation datasets and two adaptation settings
