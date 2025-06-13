---
layout: publication
title: 'Magic Pyramid: Accelerating Inference With Early Exiting And Token Pruning'
authors: Xuanli He, Iman Keivanloo, Yi Xu, Xiang He, Belinda Zeng, Santosh Rajagopalan, Trishul Chilimbi
conference: "Arxiv"
year: 2021
bibkey: he2021magic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2111.00230"}
tags: ['Fine-Tuning', 'Transformer', 'Pre-Training', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Pruning', 'Training Techniques', 'Pretraining Methods', 'BERT']
---
Pre-training and then fine-tuning large language models is commonly used to
achieve state-of-the-art performance in natural language processing (NLP)
tasks. However, most pre-trained models suffer from low inference speed.
Deploying such large models to applications with latency constraints is
challenging. In this work, we focus on accelerating the inference via
conditional computations. To achieve this, we propose a novel idea, Magic
Pyramid (MP), to reduce both width-wise and depth-wise computation via token
pruning and early exiting for Transformer-based models, particularly BERT. The
former manages to save the computation via removing non-salient tokens, while
the latter can fulfill the computation reduction by terminating the inference
early before reaching the final layer, if the exiting condition is met. Our
empirical studies demonstrate that compared to previous state of arts, MP is
not only able to achieve a speed-adjustable inference but also to surpass token
pruning and early exiting by reducing up to 70% giga floating point operations
(GFLOPs) with less than 0.5% accuracy drop. Token pruning and early exiting
express distinctive preferences to sequences with different lengths. However,
MP is capable of achieving an average of 8.06x speedup on two popular text
classification tasks, regardless of the sizes of the inputs.
