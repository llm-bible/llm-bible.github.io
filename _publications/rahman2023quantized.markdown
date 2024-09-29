---
layout: publication
title: "Quantized Transformer Language Model Implementations On Edge Devices"
authors: Rahman Mohammad Wali Ur, Abrar Murad Mehrab, Copening Hunter Gibbons, Hariri Salim, Shao Sicong, Satam Pratik, Salehi Soheil
conference: "Arxiv"
year: 2023
bibkey: rahman2023quantized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03971"}
tags: ['Applications', 'BERT', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Transformer']
---
Large-scale transformer-based models like the Bidirectional Encoder Representations from Transformers (BERT) are widely used for Natural Language Processing (NLP) applications wherein these models are initially pre-trained with a large corpus with millions of parameters and then fine-tuned for a downstream NLP task. One of the major limitations of these large-scale models is that they cannot be deployed on resource-constrained devices due to their large model size and increased inference latency. In order to overcome these limitations such large-scale models can be converted to an optimized FlatBuffer format tailored for deployment on resource-constrained edge devices. Herein we evaluate the performance of such FlatBuffer transformed MobileBERT models on three different edge devices fine-tuned for Reputation analysis of English language tweets in the RepLab 2013 dataset. In addition this study encompassed an evaluation of the deployed models wherein their latency performance and resource efficiency were meticulously assessed. Our experiment results show that compared to the original BERT large model the converted and quantized MobileBERT models have 160(times) smaller footprints for a 4.137; drop in accuracy while analyzing at least one tweet per second on edge devices. Furthermore our study highlights the privacy-preserving aspect of TinyML systems as all data is processed locally within a serverless environment.
