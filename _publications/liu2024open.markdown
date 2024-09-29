---
layout: publication
title: Omgeval\: An Open Multilingual Generative Evaluation Benchmark For Large Language Models
authors: Liu Yang, Xu Meng, Wang Shuo, Yang Liner, Wang Haoyu, Liu Zhenghao, Kong Cunliang, Chen Yun, Liu Yang, Sun Maosong, Yang Erhong
conference: "Arxiv"
year: 2024
bibkey: liu2024open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.13524"}
  - {name: "Code", url: "https://github.com/blcuicall/OMGEval"}
tags: ['GPT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning']
---
Modern large language models (LLMs) should generally benefit individuals from various cultural backgrounds around the world. However most recent advanced generative evaluation benchmarks tailed for LLMs mainly focus on English. To this end we introduce OMGEval the first Open-source Multilingual Generative test set that can assess the capability of LLMs in different languages. For each language OMGEval provides 804 open-ended questions covering a wide range of important capabilities of LLMs such as general knowledge logical reasoning and so on. Each question is rigorously verified by human annotators. Notably to sufficiently reflect the compatibility of LLMs in different cultural backgrounds we perform localization for each non-English language. Specifically the current version of OMGEval includes 5 languages (i.e. Zh Ru Fr Es Ar). Following AlpacaEval we employ GPT-4 as the adjudicator to automatically score different model outputs which is shown closely related to human evaluation. We evaluate several representative multilingual LLMs on the proposed OMGEval which we believe will provide a valuable reference for the community to further understand and improve the multilingual capability of LLMs. OMGEval is available at https://github.com/blcuicall/OMGEval."
