---
layout: publication
title: Tired of Plugins Large Language Models Can Be End-To-End Recommenders
authors: Zhang Wenlin, Wu Chuhan, Li Xiangyang, Wang Yuhao, Dong Kuicai, Wang Yichao, Dai Xinyi, Zhao Xiangyu, Guo Huifeng, Tang Ruiming
conference: "Arxiv"
year: 2024
bibkey: zhang2024tired
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00702"}
tags: ['Efficiency And Optimization', 'Interpretability And Explainability', 'Pretraining Methods', 'Tools']
---
Recommender systems aim to predict user interest based on historical behavioral data. They are mainly designed in sequential pipelines requiring lots of data to train different sub-systems and are hard to scale to new domains. Recently Large Language Models (LLMs) have demonstrated remarkable generalized capabilities enabling a singular model to tackle diverse recommendation tasks across various scenarios. Nonetheless existing LLM-based recommendation systems utilize LLM purely for a single task of the recommendation pipeline. Besides these systems face challenges in presenting large-scale item sets to LLMs in natural language format due to the constraint of input length. To address these challenges we introduce an LLM-based end-to-end recommendation framework UniLLMRec. Specifically UniLLMRec integrates multi-stage tasks (e.g. recall ranking re-ranking) via chain-of-recommendations. To deal with large-scale items we propose a novel strategy to structure all items into an item tree which can be dynamically updated and effectively retrieved. UniLLMRec shows promising zero-shot results in comparison with conventional supervised models. Additionally it boasts high efficiency reducing the input token need by 86 compared to existing LLM-based models. Such efficiency not only accelerates task completion but also optimizes resource utilization. To facilitate model understanding and to ensure reproducibility we have made our code publicly available.
