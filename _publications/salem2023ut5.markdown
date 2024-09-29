---
layout: publication
title: UT5 Pretraining Non autoregressive T5 with unrolled denoising
authors: Salem Mahmoud G., Ye Jiayu, Lin Chu-cheng, Liu Frederick
conference: "Arxiv"
year: 2023
bibkey: salem2023ut5
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08552"}
tags: ['GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recent advances in Transformer-based Large Language Models have made great strides in natural language generation. However to decode K tokens an autoregressive model needs K sequential forward passes which may be a performance bottleneck for large language models. Many non-autoregressive (NAR) research are aiming to address this sequentiality bottleneck albeit many have focused on a dedicated architecture in supervised benchmarks. In this work we studied unsupervised pretraining for non auto-regressive T5 models via unrolled denoising and shown its SoTA results in downstream generation tasks such as SQuAD question generation and XSum.
