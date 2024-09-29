---
layout: publication
title: Api-bank A Comprehensive Benchmark For Tool-augmented Llms
authors: Li Minghao, Zhao Yingxiu, Yu Bowen, Song Feifan, Li Hangyu, Yu Haiyang, Li Zhoujun, Huang Fei, Li Yongbin
conference: "Arxiv"
year: 2023
bibkey: li2023api
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.08244"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'TACL', 'Tools', 'Training Techniques']
---
Recent research has demonstrated that Large Language Models (LLMs) can enhance their capabilities by utilizing external tools. However three pivotal questions remain unanswered (1) How effective are current LLMs in utilizing tools (2) How can we enhance LLMs ability to utilize tools (3) What obstacles need to be overcome to leverage tools To address these questions we introduce API-Bank a groundbreaking benchmark specifically designed for tool-augmented LLMs. For the first question we develop a runnable evaluation system consisting of 73 API tools. We annotate 314 tool-use dialogues with 753 API calls to assess the existing LLMs capabilities in planning retrieving and calling APIs. For the second question we construct a comprehensive training set containing 1888 tool-use dialogues from 2138 APIs spanning 1000 distinct domains. Using this dataset we train Lynx a tool-augmented LLM initialized from Alpaca. Experimental results demonstrate that GPT-3.5 exhibits improved tool utilization compared to GPT-3 while GPT-4 excels in planning. However there is still significant potential for further improvement. Moreover Lynx surpasses Alpacas tool utilization performance by more than 26 pts and approaches the effectiveness of GPT-3.5. Through error analysis we highlight the key challenges for future research in this field to answer the third question.
