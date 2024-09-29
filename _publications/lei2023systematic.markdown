---
layout: publication
title: 'S3eval: A Synthetic, Scalable, Systematic Evaluation Suite For Large Language Models'
authors: Lei Fangyu, Liu Qian, Huang Yiming, He Shizhu, Zhao Jun, Liu Kang
conference: "Arxiv"
year: 2023
bibkey: lei2023systematic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.15147"}
tags: ['Ethics And Bias', 'Reinforcement Learning', 'Tools']
---
The rapid development of Large Language Models (LLMs) has led to great strides in model capabilities like long-context understanding and reasoning. However as LLMs are able to process longer contexts it becomes more challenging to evaluate whether they have acquired certain capabilities since the length of text (e.g. 200K tokens) they can process far exceeds what humans can reliably assess in a reasonable duration. In this paper we propose using complex synthetic tasks as a proxy evaluation method and present S3Eval a Synthetic Scalable Systematic evaluation suite for LLMs evaluation. The synthetic nature of S3Eval provides users full control over the dataset allowing them to systematically probe LLM capabilities by scaling text length and varying task difficulty across diverse scenarios. The strong correlation between S3Eval and real-world benchmarks demonstrates the soundness of using S3Eval for evaluation of LLMs. S3Eval provides a flexible and infinite long-context data generation method. We have generated a comprehensive dataset called S3Eval-Standard and experimental results have shown that it poses significant challenges for all existing LLMs.
