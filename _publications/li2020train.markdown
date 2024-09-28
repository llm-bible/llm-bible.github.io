---
layout: publication
title: Train Large Then Compress Rethinking Model Size for Efficient Training and Inference of Transformers
authors: Li Zhuohan, Wallace Eric, Shen Sheng, Lin Kevin, Keutzer Kurt, Klein Dan, Gonzalez Joseph E.
conference: "Arxiv"
year: 2020
bibkey: li2020train
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2002.11794"}
tags: ['ARXIV', 'Pretraining Methods', 'Pruning', 'Quantization', 'Self Supervised', 'Supervised', 'Transformer']
---
Since hardware resources are limited the objective of training deep learning models is typically to maximize accuracy subject to the time and memory constraints of training and inference. We study the impact of model size in this setting focusing on Transformer models for NLP tasks that are limited by compute self-supervised pretraining and high-resource machine translation. We first show that even though smaller Transformer models execute faster per iteration wider and deeper models converge in significantly fewer steps. Moreover this acceleration in convergence typically outpaces the additional computational overhead of using larger models. Therefore the most compute-efficient training strategy is to counterintuitively train extremely large models but stop after a small number of iterations. This leads to an apparent trade-off between the training efficiency of large Transformer models and the inference efficiency of small Transformer models. However we show that large models are more robust to compression techniques such as quantization and pruning than small models. Consequently one can get the best of both worlds heavily compressed large models achieve higher accuracy than lightly compressed small models.
