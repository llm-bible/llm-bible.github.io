---
layout: publication
title: 'Adapting Large Language Models To Log Analysis With Interpretable Domain Knowledge'
authors: Yuhe Ji, Yilun Liu, Feiyu Yao, Minggui He, Shimin Tao, Xiaofeng Zhao, Su Chang, Xinhua Yang, Weibin Meng, Yuming Xie, Boxing Chen, Hao Yang
conference: "Arxiv"
year: 2024
bibkey: ji2024adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.01377"}
tags: ['Training Techniques', 'Reinforcement Learning', 'RAG', 'Pre-Training', 'Applications']
---
The increasing complexity of computer systems necessitates innovative
approaches to fault and error management, going beyond traditional manual log
analysis. While existing solutions using large language models (LLMs) show
promise, they are limited by a gap between natural and domain-specific
languages, which restricts their effectiveness in real-world applications. Our
approach addresses these limitations by integrating interpretable domain
knowledge into open-source LLMs through continual pre-training (CPT), enhancing
performance on log tasks while retaining natural language processing
capabilities. We created a comprehensive dataset, NLPLog, with over 250,000
question-answer pairs to facilitate this integration. Our model, SuperLog,
trained with this dataset, achieves the best performance across four log
analysis tasks, surpassing the second-best model by an average of 12.01%. Our
contributions include a novel CPT paradigm that significantly improves model
performance, the development of SuperLog with state-of-the-art results, and the
release of a large-scale dataset to support further research in this domain.
