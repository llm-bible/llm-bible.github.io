---
layout: publication
title: Who Says Elephants Can't Run: Bringing Large Scale Moe Models Into Cloud Scale Production
authors: Kim Young Jin, Henry Rawn, Fahim Raffy, Awadalla Hany Hassan
conference: "Arxiv"
year: 2022
bibkey: kim2022who
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.10017"}
tags: ['Applications', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Mixture of Experts (MoE) models with conditional execution of sparsely activated layers have enabled training models with a much larger number of parameters. As a result these models have achieved significantly better quality on various natural language processing tasks including machine translation. However it remains challenging to deploy such models in real-life scenarios due to the large memory requirements and inefficient inference. In this work we introduce a highly efficient inference framework with several optimization approaches to accelerate the computation of sparse models and cut down the memory consumption significantly. While we achieve up to 26x speed-up in terms of throughput we also reduce the model size almost to one eighth of the original 32-bit float model by quantizing expert weights into 4-bit integers. As a result we are able to deploy 136x larger models with 2737; less cost and significantly better quality compared to the existing solutions. This enables a paradigm shift in deploying large scale multilingual MoE transformers models replacing the traditional practice of distilling teacher models into dozens of smaller models per language or task.
