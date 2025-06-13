---
layout: publication
title: 'Targeted Distillation For Sentiment Analysis'
authors: Yice Zhang, Guangyu Xie, Jingjie Lin, Jianzhu Bao, Qianlong Wang, Xi Zeng, Ruifeng Xu
conference: "Arxiv"
year: 2025
bibkey: zhang2025targeted
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.03225"}
tags: ['Efficiency and Optimization', 'Tools', 'Distillation', 'Prompting', 'In-Context Learning']
---
This paper presents a compact model that achieves strong sentiment analysis
capabilities through targeted distillation from advanced large language models
(LLMs). Our methodology decouples the distillation target into two key
components: sentiment-related knowledge and task alignment. To transfer these
components, we propose a two-stage distillation framework. The first stage,
knowledge-driven distillation (\textsc\{KnowDist\}), transfers sentiment-related
knowledge to enhance fundamental sentiment analysis capabilities. The second
stage, in-context learning distillation (\textsc\{ICLDist\}), transfers
task-specific prompt-following abilities to optimize task alignment. For
evaluation, we introduce \textsc\{SentiBench\}, a comprehensive sentiment
analysis benchmark comprising 3 task categories across 12 datasets. Experiments
on this benchmark demonstrate that our model effectively balances model size
and performance, showing strong competitiveness compared to existing
small-scale LLMs.
