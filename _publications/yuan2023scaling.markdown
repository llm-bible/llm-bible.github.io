---
layout: publication
title: Scaling Relationship On Learning Mathematical Reasoning With Large Language Models
authors: Yuan Zheng, Yuan Hongyi, Li Chengpeng, Dong Guanting, Lu Keming, Tan Chuanqi, Zhou Chang, Zhou Jingren
conference: "Arxiv"
year: 2023
bibkey: yuan2023scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.01825"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Mathematical reasoning is a challenging task for large language models (LLMs) while the scaling relationship of it with respect to LLM capacity is under45;explored. In this paper we investigate how the pre45;training loss supervised data amount and augmented data amount influence the reasoning performances of a supervised LLM. We find that pre45;training loss is a better indicator of the models performance than the models parameter count. We apply supervised fine45;tuning (SFT) with different amounts of supervised data and empirically find a log45;linear relation between data amount and model performance and we find better models improve less with enlarged supervised datasets. To augment more data samples for improving model performances without any human effort we propose to apply Rejection sampling Fine45;Tuning (RFT). RFT uses supervised models to generate and collect correct reasoning paths as augmented fine45;tuning datasets. We find with augmented samples containing more distinct reasoning paths RFT improves mathematical reasoning performance more for LLMs. We also find RFT brings more improvement for less performant LLMs. Furthermore we combine rejection samples from multiple models which push LLaMA45;7B to an accuracy of 49.337; on GSM8K which outperforms the supervised fine45;tuning (SFT) accuracy of 35.937; significantly.
