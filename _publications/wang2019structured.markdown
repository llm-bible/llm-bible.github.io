---
layout: publication
title: Structured Pruning Of Large Language Models
authors: Wang Ziheng, Wohlwend Jeremy, Lei Tao
conference: "Arxiv"
year: 2019
bibkey: wang2019structured
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1910.04732"}
tags: ['BERT', 'Efficiency And Optimization', 'Language Modeling', 'Model Architecture', 'Pruning', 'Quantization', 'Training Techniques']
---
Large language models have recently achieved state of the art performance across a wide variety of natural language tasks. Meanwhile the size of these models and their latency have significantly increased which makes their usage costly and raises an interesting question do language models need to be large We study this question through the lens of model compression. We present a generic structured pruning approach by parameterizing each weight matrix using its low45;rank factorization and adaptively removing rank45;1 components during training. On language modeling tasks our structured approach outperforms other unstructured and block45;structured pruning baselines at various compression levels while achieving significant speedups during both training and inference. We also demonstrate that our method can be applied to pruning adaptive word embeddings in large language models and to pruning the BERT model on several downstream fine45;tuning classification benchmarks.
