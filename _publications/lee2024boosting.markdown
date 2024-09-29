---
layout: publication
title: LLM2LLM Boosting Llms With Novel Iterative Data Enhancement
authors: Lee Nicholas, Wattanawong Thanakul, Kim Sehoon, Mangalam Karttikeya, Shen Sheng, Anumanchipalli Gopala, Mahoney Michael W., Keutzer Kurt, Gholami Amir
conference: "Arxiv"
year: 2024
bibkey: lee2024boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15042"}
  - {name: "Code", url: "https://github.com/SqueezeAILab/LLM2LLM"}
tags: ['Applications', 'Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
Pretrained large language models (LLMs) are currently state45;of45;the45;art for solving the vast majority of natural language processing tasks. While many real45;world applications still require fine45;tuning to reach satisfactory levels of performance many of them are in the low45;data regime making fine45;tuning challenging. To address this we propose LLM2LLM a targeted and iterative data augmentation strategy that uses a teacher LLM to enhance a small seed dataset by augmenting additional data that can be used for fine45;tuning on a specific task. LLM2LLM (1) fine45;tunes a baseline student LLM on the initial seed data (2) evaluates and extracts data points that the model gets wrong and (3) uses a teacher LLM to generate synthetic data based on these incorrect data points which are then added back into the training data. This approach amplifies the signal from incorrectly predicted data points by the LLM during training and reintegrates them into the dataset to focus on more challenging examples for the LLM. Our results show that LLM2LLM significantly enhances the performance of LLMs in the low45;data regime outperforming both traditional fine45;tuning and other data augmentation baselines. LLM2LLM reduces the dependence on labor45;intensive data curation and paves the way for more scalable and performant LLM solutions allowing us to tackle data45;constrained domains and tasks. We achieve improvements up to 24.237; on the GSM8K dataset 32.637; on CaseHOLD 32.037; on SNIPS 52.637; on TREC and 39.837; on SST45;2 over regular fine45;tuning in the low45;data regime using a Llama45;245;7B student model. Our code is available at https://github.com/SqueezeAILab/LLM2LLM .
