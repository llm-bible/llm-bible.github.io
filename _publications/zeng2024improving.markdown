---
layout: publication
title: Improving Logits-based Detector without Logits from Black-box LLMs
authors: Zeng Cong, Tang Shengkun, Yang Xianjun, Chen Yuanzhou, Sun Yiyou, Xu Zhiqiang, Li Yao, Chen Haifeng, Cheng Wei, Xu Dongkuan
conference: "Arxiv"
year: 2024
bibkey: zeng2024improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.05232"}
tags: ['ARXIV', 'Chatgpt', 'GPT', 'LLM', 'Language Modeling', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Tools']
---
The advent of Large Language Models (LLMs) has revolutionized text generation producing outputs that closely mimic human writing. This blurring of lines between machine- and human-written text presents new challenges in distinguishing one from the other a task further complicated by the frequent updates and closed nature of leading proprietary LLMs. Traditional logits-based detection methods leverage surrogate models for identifying LLM-generated content when the exact logits are unavailable from black-box LLMs. However these methods grapple with the misalignment between the distributions of the surrogate and the often undisclosed target models leading to performance degradation particularly with the introduction of new closed-source models. Furthermore while current methodologies are generally effective when the source model is identified they falter in scenarios where the model version remains unknown or the test set comprises outputs from various source models. To address these limitations we present Distribution-Aligned LLMs Detection (DALD) an innovative framework that redefines the state-of-the-art performance in black-box text detection even without logits from source LLMs. DALD is designed to align the surrogate models distribution with that of unknown target LLMs ensuring enhanced detection capability and resilience against rapid model iterations with minimal training investment. By leveraging corpus samples from publicly accessible outputs of advanced models such as ChatGPT GPT-4 and Claude-3 DALD fine-tunes surrogate models to synchronize with unknown source model distributions effectively.
