---
layout: publication
title: 'Kalm-embedding: Superior Training Data Brings A Stronger Embedding Model'
authors: Xinshuo Hu, Zifei Shan, Xinping Zhao, Zetian Sun, Zhenyu Liu, Dongfang Li, Shaolin Ye, Xinyuan Wei, Qian Chen, Baotian Hu, Haofen Wang, Jun Yu, Min Zhang
conference: "Arxiv"
year: 2025
bibkey: hu2025kalm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.01028"}
tags: ['RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'BERT']
---
As retrieval-augmented generation prevails in large language models,
embedding models are becoming increasingly crucial. Despite the growing number
of general embedding models, prior work often overlooks the critical role of
training data quality. In this work, we introduce KaLM-Embedding, a general
multilingual embedding model that leverages a large quantity of cleaner, more
diverse, and domain-specific training data. Our model has been trained with key
techniques proven to enhance performance: (1) persona-based synthetic data to
create diversified examples distilled from LLMs, (2) ranking consistency
filtering to remove less informative samples, and (3) semi-homogeneous task
batch sampling to improve training efficacy. Departing from traditional
BERT-like architectures, we adopt Qwen2-0.5B as the pre-trained model,
facilitating the adaptation of auto-regressive language models for general
embedding tasks. Extensive evaluations of the MTEB benchmark across multiple
languages show that our model outperforms others of comparable size, setting a
new standard for multilingual embedding models with <1B parameters.
