---
layout: publication
title: "Language Models Are Universal Embedders"
authors: Zhang Xin, Li Zehan, Zhang Yanzhao, Long Dingkun, Xie Pengjun, Zhang Meishan, Zhang Min
conference: "Arxiv"
year: 2023
bibkey: zhang2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.08232"}
tags: ['Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
In the large language model (LLM) revolution embedding is a key component of various systems. For example it is used to retrieve knowledge or memories for LLMs to build content moderation filters etc. As such cases span from English to other natural or programming languages from retrieval to classification and beyond it is desirable to build a unified embedding model rather than dedicated ones for each scenario. In this work we make an initial step towards this goal demonstrating that multiple languages (both natural and programming) pre-trained transformer decoders can embed universally when finetuned on limited English data. We provide a comprehensive practice with thorough evaluations. On English MTEB our models achieve competitive performance on different embedding tasks by minimal training data. On other benchmarks such as multilingual classification and code search our models (without any supervision) perform comparably to or even surpass heavily supervised baselines and/or APIs. These results provide evidence of a promising path towards building powerful unified embedders that can be applied across tasks and languages.
