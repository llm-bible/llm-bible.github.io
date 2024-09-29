---
layout: publication
title: LARR Large Language Model Aided Real45;time Scene Recommendation With Semantic Understanding
authors: Wan Zhizhong, Yin Bin, Xie Junjie, Jiang Fei, Li Xiang, Lin Wei
conference: "Arxiv"
year: 2024
bibkey: wan2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11523"}
tags: ['Efficiency And Optimization', 'Pretraining Methods']
---
Click45;Through Rate (CTR) prediction is crucial for Recommendation System(RS) aiming to provide personalized recommendation services for users in many aspects such as food delivery e45;commerce and so on. However traditional RS relies on collaborative signals which lacks semantic understanding to real45;time scenes. We also noticed that a major challenge in utilizing Large Language Models (LLMs) for practical recommendation purposes is their efficiency in dealing with long text input. To break through the problems above we propose Large Language Model Aided Real45;time Scene Recommendation(LARR) adopt LLMs for semantic understanding utilizing real45;time scene information in RS without requiring LLM to process the entire real45;time scene text directly thereby enhancing the efficiency of LLM45;based CTR modeling. Specifically recommendation domain45;specific knowledge is injected into LLM and then RS employs an aggregation encoder to build real45;time scene information from separate LLMs outputs. Firstly a LLM is continual pretrained on corpus built from recommendation data with the aid of special tokens. Subsequently the LLM is fine45;tuned via contrastive learning on three kinds of sample construction strategies. Through this step LLM is transformed into a text embedding model. Finally LLMs separate outputs for different scene features are aggregated by an encoder aligning to collaborative signals in RS enhancing the performance of recommendation model.
