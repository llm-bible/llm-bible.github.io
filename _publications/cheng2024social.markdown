---
layout: publication
title: Social Debiasing For Fair Multi-modal Llms
authors: Cheng Harry, Guo Yangyang, Guo Qingpei, Yang Ming, Gan Tian, Nie Liqiang
conference: "Arxiv"
year: 2024
bibkey: cheng2024social
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.06569"}
tags: ['Ethics And Bias', 'GPT', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques']
---
Multi-modal Large Language Models (MLLMs) have advanced significantly offering powerful vision-language understanding capabilities. However these models often inherit severe social biases from their training datasets leading to unfair predictions based on attributes like race and gender. This paper addresses the issue of social biases in MLLMs by i) Introducing a comprehensive Counterfactual dataset with Multiple Social Concepts (CMSC) which provides a more diverse and extensive training set compared to existing datasets. ii) Proposing an Anti-Stereotype Debiasing strategy (ASD). Our method works by revisiting the MLLM training process rescaling the autoregressive loss function and improving data sampling methods to counteract biases. Through extensive experiments on various MLLMs our CMSC dataset and ASD method demonstrate a significant reduction in social biases while maintaining the models original performance.
