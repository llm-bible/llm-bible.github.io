---
layout: publication
title: Empirical Guidelines for Deploying LLMs onto Resource-constrained Edge Devices
authors: Qin Ruiyang, Liu Dancheng, Yan Zheyu, Tan Zhaoxuan, Pan Zixuan, Jia Zhenge, Jiang Meng, Abbasi Ahmed, Xiong Jinjun, Shi Yiyu
conference: "Arxiv"
year: 2024
bibkey: qin2024empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.03777"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Large Scale Training', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Scaling Laws', 'Training Techniques']
---
The scaling laws have become the de facto guidelines for designing large language models (LLMs) but they were studied under the assumption of unlimited computing resources for both training and inference. As LLMs are increasingly used as personalized intelligent assistants their customization (i.e. learning through fine-tuning) and deployment onto resource-constrained edge devices will become more and more prevalent. An urging but open question is how a resource-constrained computing environment would affect the design choices for a personalized LLM. We study this problem empirically in this work. In particular we consider the tradeoffs among a number of key design factors and their intertwined impacts on learning efficiency and accuracy. The factors include the learning methods for LLM customization the amount of personalized data used for learning customization the types and sizes of LLMs the compression methods of LLMs the amount of time afforded to learn and the difficulty levels of the target use cases. Through extensive experimentation and benchmarking we draw a number of surprisingly insightful guidelines for deploying LLMs onto resource-constrained devices. For example an optimal choice between parameter learning and RAG may vary depending on the difficulty of the downstream task the longer fine-tuning time does not necessarily help the model and a compressed LLM may be a better choice than an uncompressed LLM to learn from limited personalized data.
