---
layout: publication
title: 'Scaling Transformers For Discriminative Recommendation Via Generative Pretraining'
authors: Chunqi Wang, Bingchao Wu, Zheng Chen, Lei Shen, Bing Wang, Xiaoyi Zeng
conference: "Arxiv"
year: 2025
bibkey: wang2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03699"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'RAG', 'RecSys', 'Pretraining Methods', 'Transformer']
---
Discriminative recommendation tasks, such as CTR (click-through rate) and CVR (conversion rate) prediction, play critical roles in the ranking stage of large-scale industrial recommender systems. However, training a discriminative model encounters a significant overfitting issue induced by data sparsity. Moreover, this overfitting issue worsens with larger models, causing them to underperform smaller ones. To address the overfitting issue and enhance model scalability, we propose a framework named GPSD (\textbf\{G\}enerative \textbf\{P\}retraining for \textbf\{S\}calable \textbf\{D\}iscriminative Recommendation), drawing inspiration from generative training, which exhibits no evident signs of overfitting. GPSD leverages the parameters learned from a pretrained generative model to initialize a discriminative model, and subsequently applies a sparse parameter freezing strategy. Extensive experiments conducted on both industrial-scale and publicly available datasets demonstrate the superior performance of GPSD. Moreover, it delivers remarkable improvements in online A/B tests. GPSD offers two primary advantages: 1) it substantially narrows the generalization gap in model training, resulting in better test performance; and 2) it leverages the scalability of Transformers, delivering consistent performance gains as models are scaled up. Specifically, we observe consistent performance improvements as the model dense parameters scale from 13K to 0.3B, closely adhering to power laws. These findings pave the way for unifying the architectures of recommendation models and language models, enabling the direct application of techniques well-established in large language models to recommendation models.
