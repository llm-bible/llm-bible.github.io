---
layout: publication
title: Q Improving Multi-step Reasoning for LLMs with Deliberative Planning
authors: Wang Chaojie, Deng Yanchen, Lyu Zhiyi, Zeng Liang, He Jujie, Yan Shuicheng, An Bo
conference: "Arxiv"
year: 2024
bibkey: wang2024q
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14283"}
tags: ['ARXIV', 'Fine Tuning', 'LLM', 'Pretraining Methods', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have demonstrated impressive capability in many natural language tasks. However the auto-regressive generation process makes LLMs prone to produce errors hallucinations and inconsistent statements when performing multi-step reasoning. In this paper by casting multi-step reasoning of LLMs as a heuristic search problem we aim to alleviate the pathology by introducing Q a general versatile and agile framework for guiding LLMs decoding process with deliberative planning. By learning a plug-and-play Q-value model as heuristic function for estimating expected future rewards our Q can effectively guide LLMs to select the most promising next reasoning step without fine-tuning LLMs for the current task which avoids the significant computational overhead and potential risk of performance degeneration on other tasks. Extensive experiments on GSM8K MATH and MBPP demonstrate the superiority of our method contributing to improving the reasoning performance of existing open-source LLMs.
