---
layout: publication
title: Enhancing Inference Efficiency Of Large Language Models\: Investigating Optimization Strategies And Architectural Innovations
authors: Tyukin Georgy
conference: "Arxiv"
year: 2024
bibkey: tyukin2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.05741"}
tags: ['Attention Mechanism', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Quantization', 'Transformer']
---
Large Language Models are growing in size and we expect them to continue to do so as larger models train quicker. However this increase in size will severely impact inference costs. Therefore model compression is important to retain the performance of larger models but with a reduced cost of running them. In this thesis we explore the methods of model compression and we empirically demonstrate that the simple method of skipping latter attention sublayers in Transformer LLMs is an effective method of model compression as these layers prove to be redundant whilst also being incredibly computationally expensive. We observed a 2137; speed increase in one-token generation for Llama 2 7B whilst surprisingly and unexpectedly improving performance over several common benchmarks.
