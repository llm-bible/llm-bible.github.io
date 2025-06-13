---
layout: publication
title: 'Learning More Effective Representations For Dense Retrieval Through Deliberate Thinking Before Search'
authors: Yifan Ji, Zhipeng Xu, Zhenghao Liu, Yukun Yan, Shi Yu, Yishan Li, Zhiyuan Liu, Yu Gu, Ge Yu, Maosong Sun
conference: "Arxiv"
year: 2025
bibkey: ji2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12974"}
  - {name: "Code", url: "https://github.com/OpenBMB/DEBATER"}
tags: ['Security', 'Efficiency and Optimization', 'Has Code', 'Distillation']
---
Recent dense retrievers usually thrive on the emergency capabilities of Large
Language Models (LLMs), using them to encode queries and documents into an
embedding space for retrieval. These LLM-based dense retrievers have shown
promising performance across various retrieval scenarios. However, relying on a
single embedding to represent documents proves less effective in capturing
different perspectives of documents for matching. In this paper, we propose
Deliberate Thinking based Dense Retriever (DEBATER), which enhances these
LLM-based retrievers by enabling them to learn more effective document
representations through a step-by-step thinking process. DEBATER introduces the
Chain-of-Deliberation mechanism to iteratively optimize document
representations using a continuous chain of thought. To consolidate information
from various thinking steps, DEBATER also incorporates the Self Distillation
mechanism, which identifies the most informative thinking steps and integrates
them into a unified text embedding. Experimental results show that DEBATER
significantly outperforms existing methods across several retrieval benchmarks,
demonstrating superior accuracy and robustness. All codes are available at
https://github.com/OpenBMB/DEBATER.
