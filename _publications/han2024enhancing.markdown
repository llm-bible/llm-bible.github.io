---
layout: publication
title: Enhancing CTR Prediction Through Sequential Recommendation Pre45;training Introducing The SRP4CTR Framework
authors: Han Ruidong, Li Qianzhong, Jiang He, Li Rui, Zhao Yurou, Li Xiang, Lin Wei
conference: "Arxiv"
year: 2024
bibkey: han2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19658"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Understanding user interests is crucial for Click45;Through Rate (CTR) prediction tasks. In sequential recommendation pre45;training from user historical behaviors through self45;supervised learning can better comprehend user dynamic preferences presenting the potential for direct integration with CTR tasks. Previous methods have integrated pre45;trained models into downstream tasks with the sole purpose of extracting semantic information or well45;represented user features which are then incorporated as new features. However these approaches tend to ignore the additional inference costs to the downstream tasks and they do not consider how to transfer the effective information from the pre45;trained models for specific estimated items in CTR prediction. In this paper we propose a Sequential Recommendation Pre45;training framework for CTR prediction (SRP4CTR) to tackle the above problems. Initially we discuss the impact of introducing pre45;trained models on inference costs. Subsequently we introduced a pre45;trained method to encode sequence side information concurrently.During the fine45;tuning process we incorporate a cross45;attention block to establish a bridge between estimated items and the pre45;trained model at a low cost. Moreover we develop a querying transformer technique to facilitate the knowledge transfer from the pre45;trained model to industrial CTR models. Offline and online experiments show that our method outperforms previous baseline models.
