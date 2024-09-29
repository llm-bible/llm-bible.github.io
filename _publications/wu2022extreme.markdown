---
layout: publication
title: Extreme Compression For Pre45;trained Transformers Made Simple And Efficient
authors: Wu Xiaoxia, Yao Zhewei, Zhang Minjia, Li Conglong, He Yuxiong
conference: "Arxiv"
year: 2022
bibkey: wu2022extreme
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2206.01859"}
tags: ['BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Extreme compression particularly ultra45;low bit precision (binary/ternary) quantization has been proposed to fit large NLP models on resource45;constraint devices. However to preserve the accuracy for such aggressive compression schemes cutting45;edge methods usually introduce complicated compression pipelines e.g. multi45;stage expensive knowledge distillation with extensive hyperparameter tuning. Also they oftentimes focus less on smaller transformer models that have already been heavily compressed via knowledge distillation and lack a systematic study to show the effectiveness of their methods. In this paper we perform a very comprehensive systematic study to measure the impact of many key hyperparameters and training strategies from previous works. As a result we find out that previous baselines for ultra45;low bit precision quantization are significantly under45;trained. Based on our study we propose a simple yet effective compression pipeline for extreme compression named XTC. XTC demonstrates that (1) we can skip the pre45;training knowledge distillation to obtain a 545;layer BERT while achieving better performance than previous state45;of45;the45;art methods e.g. the 645;layer TinyBERT; (2) extreme quantization plus layer reduction is able to reduce the model size by 50x resulting in new state45;of45;the45;art results on GLUE tasks.
