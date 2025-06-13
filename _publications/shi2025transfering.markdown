---
layout: publication
title: 'Latte: Transfering Llms` Latent-level Knowledge For Few-shot Tabular Learning'
authors: Ruxue Shi, Hengrui Gu, Hangting Ye, Yiwei Dai, Xu Shen, Xin Wang
conference: "Arxiv"
year: 2025
bibkey: shi2025transfering
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05237"}
tags: ['Pre-Training', 'Tools', 'RAG', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Few-Shot']
---
Few-shot tabular learning, in which machine learning models are trained with
a limited amount of labeled data, provides a cost-effective approach to
addressing real-world challenges. The advent of Large Language Models (LLMs)
has sparked interest in leveraging their pre-trained knowledge for few-shot
tabular learning. Despite promising results, existing approaches either rely on
test-time knowledge extraction, which introduces undesirable latency, or
text-level knowledge, which leads to unreliable feature engineering. To
overcome these limitations, we propose Latte, a training-time knowledge
extraction framework that transfers the latent prior knowledge within LLMs to
optimize a more generalized downstream model. Latte enables general
knowledge-guided downstream tabular learning, facilitating the weighted fusion
of information across different feature values while reducing the risk of
overfitting to limited labeled data. Furthermore, Latte is compatible with
existing unsupervised pre-training paradigms and effectively utilizes available
unlabeled samples to overcome the performance limitations imposed by an
extremely small labeled dataset. Extensive experiments on various few-shot
tabular learning benchmarks demonstrate the superior performance of Latte,
establishing it as a state-of-the-art approach in this domain
