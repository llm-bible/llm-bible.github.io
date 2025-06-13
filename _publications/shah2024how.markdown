---
layout: publication
title: 'How Effectively Do Llms Extract Feature-sentiment Pairs From App Reviews?'
authors: Faiz Ali Shah, Ahmed Sabir, Rajesh Sharma, Dietmar Pfahl
conference: "Arxiv"
year: 2024
bibkey: shah2024how
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.07162'}
tags: ['GPT', 'BERT', 'Model Architecture']
---
Automatic analysis of user reviews to understand user sentiments toward app
functionality (i.e. app features) helps align development efforts with user
expectations and needs. Recent advances in Large Language Models (LLMs) such as
ChatGPT have shown impressive performance on several new tasks without updating
the model's parameters i.e. using zero or a few labeled examples, but the
capabilities of LLMs are yet unexplored for feature-specific sentiment
analysis. The goal of our study is to explore the capabilities of LLMs to
perform feature-specific sentiment analysis of user reviews. This study
compares the performance of state-of-the-art LLMs, including GPT-4, ChatGPT,
and different variants of Llama-2 chat, against previous approaches for
extracting app features and associated sentiments in zero-shot, 1-shot, and
5-shot scenarios. The results indicate that GPT-4 outperforms the rule-based
SAFE by 17% in f1-score for extracting app features in the zero-shot scenario,
with 5-shot further improving it by 6%. However, the fine-tuned RE-BERT exceeds
GPT-4 by 6% in f1-score. For predicting positive and neutral sentiments, GPT-4
achieves f1-scores of 76% and 45% in the zero-shot setting, which improve by 7%
and 23% in the 5-shot setting, respectively. Our study conducts a thorough
evaluation of both proprietary and open-source LLMs to provide an objective
assessment of their performance in extracting feature-sentiment pairs.
