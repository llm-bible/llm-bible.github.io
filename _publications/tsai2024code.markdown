---
layout: publication
title: Code Less Align More Efficient LLM Fine-tuning For Code Generation With Data Pruning
authors: Tsai Yun-da, Liu Mingjie, Ren Haoxing
conference: "Arxiv"
year: 2024
bibkey: tsai2024code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05040"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Pretraining Methods', 'Pruning', 'Training Techniques']
---
Recent work targeting large language models (LLMs) for code generation demonstrated that increasing the amount of training data through synthetic code generation often leads to exceptional performance. In this paper we explore data pruning methods aimed at enhancing the efficiency of model training specifically for code LLMs. We present techniques that integrate various clustering and pruning metrics to selectively reduce training data without compromising the accuracy and functionality of the generated code. We observe significant redundancies in synthetic training data generation where our experiments demonstrate that benchmark performance can be largely preserved by training on only 1037; of the data. Moreover we observe consistent improvements in benchmark results through moderate pruning of the training data. Our experiments show that these pruning strategies not only reduce the computational resources needed but also enhance the overall quality code generation.
