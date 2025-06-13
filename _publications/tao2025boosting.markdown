---
layout: publication
title: 'Epicode: Boosting Model Performance Beyond Training With Extrapolation And Contrastive Decoding'
authors: Mingxu Tao, Jie Hu, Mingchuan Yang, Yunhuai Liu, Dongyan Zhao, Yansong Feng
conference: "Arxiv"
year: 2025
bibkey: tao2025boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03489"}
tags: ['Training Techniques', 'Tools']
---
The remarkable performance of Large language models (LLMs) relies heavily on the availability of abundant high-quality training data. However, the high cost of acquiring annotated data often prevents models from obtaining capabilities to tackle downstream tasks. In this paper, we introduce a novel method, EpiCoDe that boosts model performance in data-scarcity scenarios without extra training. We first employ model extrapolation to enhance a finetuned model with its inferior version, and then adopt contrastive decoding to further reduce predicted errors, by comparing the logit scores given by the extrapolated and the vanilla finetuned model. Experiments across three tasks over four different LLMs show that EpiCoDe consistently outperforms existing methods with significant and robust improvement. We also propose a new theoretical framework to reveal the mechanism behind contrastive decoding in data-scarcity scenarios, which further helps us better understand the effectiveness of EpiCoDe.
