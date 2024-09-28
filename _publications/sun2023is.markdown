---
layout: publication
title: Is ChatGPT Good at Search Investigating Large Language Models as Re-Ranking Agents
authors: Sun Weiwei, Yan Lingyong, Ma Xinyu, Wang Shuaiqiang, Ren Pengjie, Chen Zhumin, Yin Dawei, Ren Zhaochun
conference: "Arxiv"
year: 2023
bibkey: sun2023is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.09542"}
tags: ['ARXIV', 'Agentic', 'Applications', 'Chatgpt', 'Distillation', 'Efficiency And Optimization', 'GPT', 'LLM', 'Reinforcement Learning']
---
Large Language Models (LLMs) have demonstrated remarkable zero-shot generalization across various language-related tasks including search engines. However existing work utilizes the generative ability of LLMs for Information Retrieval (IR) rather than direct passage ranking. The discrepancy between the pre-training objectives of LLMs and the ranking objective poses another challenge. In this paper we first investigate generative LLMs such as ChatGPT and GPT-4 for relevance ranking in IR. Surprisingly our experiments reveal that properly instructed LLMs can deliver competitive even superior results to state-of-the-art supervised methods on popular IR benchmarks. Furthermore to address concerns about data contamination of LLMs we collect a new test set called NovelEval based on the latest knowledge and aiming to verify the models ability to rank unknown knowledge. Finally to improve efficiency in real-world applications we delve into the potential for distilling the ranking capabilities of ChatGPT into small specialized models using a permutation distillation scheme. Our evaluation results turn out that a distilled 440M model outperforms a 3B supervised model on the BEIR benchmark. The code to reproduce our results is available at www.github.com/sunnweiwei/RankGPT.
