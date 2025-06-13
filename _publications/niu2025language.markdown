---
layout: publication
title: 'Langtime: A Language-guided Unified Model For Time Series Forecasting With Proximal Policy Optimization'
authors: Wenzhe Niu, Zongxia Xie, Yanru Sun, Wei He, Man Xu, Chao Hao
conference: "Arxiv"
year: 2025
bibkey: niu2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08271"}
tags: ['Fine-Tuning', 'Pre-Training', 'Efficiency and Optimization', 'Tools', 'Applications', 'GPT', 'Agentic', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models', 'Prompting']
---
Recent research has shown an increasing interest in utilizing pre-trained
large language models (LLMs) for a variety of time series applications.
However, there are three main challenges when using LLMs as foundational models
for time series forecasting: (1) Cross-domain generalization. (2)
Cross-modality alignment. (3) Error accumulation in autoregressive frameworks.
To address these challenges, we proposed LangTime, a language-guided unified
model for time series forecasting that incorporates cross-domain pre-training
with reinforcement learning-based fine-tuning. Specifically, LangTime
constructs Temporal Comprehension Prompts (TCPs), which include dataset-wise
and channel-wise instructions, to facilitate domain adaptation and condense
time series into a single token, enabling LLMs to understand better and align
temporal data. To improve autoregressive forecasting, we introduce TimePPO, a
reinforcement learning-based fine-tuning algorithm. TimePPO mitigates error
accumulation by leveraging a multidimensional rewards function tailored for
time series and a repeat-based value estimation strategy. Extensive experiments
demonstrate that LangTime achieves state-of-the-art cross-domain forecasting
performance, while TimePPO fine-tuning effectively enhances the stability and
accuracy of autoregressive forecasting.
