---
layout: publication
title: 'LARR: Large Language Model Aided Real-time Scene Recommendation With Semantic Understanding'
authors: Zhizhong Wan, Bin Yin, Junjie Xie, Fei Jiang, Xiang Li, Wei Lin
conference: "Arxiv"
year: 2024
bibkey: wan2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11523"}
tags: ['Efficiency and Optimization', 'Pretraining Methods']
---
Click-Through Rate (CTR) prediction is crucial for Recommendation System(RS),
aiming to provide personalized recommendation services for users in many
aspects such as food delivery, e-commerce and so on. However, traditional RS
relies on collaborative signals, which lacks semantic understanding to
real-time scenes. We also noticed that a major challenge in utilizing Large
Language Models (LLMs) for practical recommendation purposes is their
efficiency in dealing with long text input. To break through the problems
above, we propose Large Language Model Aided Real-time Scene
Recommendation(LARR), adopt LLMs for semantic understanding, utilizing
real-time scene information in RS without requiring LLM to process the entire
real-time scene text directly, thereby enhancing the efficiency of LLM-based
CTR modeling. Specifically, recommendation domain-specific knowledge is
injected into LLM and then RS employs an aggregation encoder to build real-time
scene information from separate LLM's outputs. Firstly, a LLM is continual
pretrained on corpus built from recommendation data with the aid of special
tokens. Subsequently, the LLM is fine-tuned via contrastive learning on three
kinds of sample construction strategies. Through this step, LLM is transformed
into a text embedding model. Finally, LLM's separate outputs for different
scene features are aggregated by an encoder, aligning to collaborative signals
in RS, enhancing the performance of recommendation model.
