---
layout: publication
title: Ernie45;tiny A Progressive Distillation Framework For Pretrained Transformer Compression
authors: Su Weiyue, Chen Xuyi, Feng Shikun, Liu Jiaxiang, Liu Weixin, Sun Yu, Tian Hao, Wu Hua, Wang Haifeng
conference: "Arxiv"
year: 2021
bibkey: su2021ernie
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.02241"}
tags: ['Applications', 'BERT', 'Distillation', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Pretrained language models (PLMs) such as BERT adopt a training paradigm which first pretrain the model in general data and then finetune the model on task45;specific data and have recently achieved great success. However PLMs are notorious for their enormous parameters and hard to be deployed on real45;life applications. Knowledge distillation has been prevailing to address this problem by transferring knowledge from a large teacher to a much smaller student over a set of data. We argue that the selection of thee three key components namely teacher training data and learning objective is crucial to the effectiveness of distillation. We therefore propose a four45;stage progressive distillation framework ERNIE45;Tiny to compress PLM which varies the three components gradually from general level to task45;specific level. Specifically the first stage General Distillation performs distillation with guidance from pretrained teacher gerenal data and latent distillation loss. Then General45;Enhanced Distillation changes teacher model from pretrained teacher to finetuned teacher. After that Task45;Adaptive Distillation shifts training data from general data to task45;specific data. In the end Task45;Specific Distillation adds two additional losses namely Soft45;Label and Hard45;Label loss onto the last stage. Empirical results demonstrate the effectiveness of our framework and generalization gain brought by ERNIE45;Tiny.In particular experiments show that a 445;layer ERNIE45;Tiny maintains over 98.037;performance of its 1245;layer teacher BERT base on GLUE benchmark surpassing state45;of45;the45;art (SOTA) by 1.037; GLUE score with the same amount of parameters. Moreover ERNIE45;Tiny achieves a new compression SOTA on five Chinese NLP tasks outperforming BERT base by 0.437; accuracy with 7.5x fewer parameters and9.4x faster inference speed.
