---
layout: publication
title: 'Fast Distilbert On Cpus'
authors: Haihao Shen, Ofir Zafrir, Bo Dong, Hengyu Meng, Xinyu Ye, Zhe Wang, Yi Ding, Hanwen Chang, Guy Boudoukh, Moshe Wasserblat
conference: "Arxiv"
year: 2022
bibkey: shen2022fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2211.07715"}
  - {name: "Code", url: "https://github.com/intel/intel-extension-for-transformers"}
tags: ['Transformer', 'Efficiency and Optimization', 'Pruning', 'Model Architecture', 'Has Code', 'Pretraining Methods', 'BERT', 'Quantization', 'Distillation']
---
Transformer-based language models have become the standard approach to
solving natural language processing tasks. However, industry adoption usually
requires the maximum throughput to comply with certain latency constraints that
prevents Transformer models from being used in production. To address this gap,
model compression techniques such as quantization and pruning may be used to
improve inference efficiency. However, these compression techniques require
specialized software to apply and deploy at scale. In this work, we propose a
new pipeline for creating and running Fast Transformer models on CPUs,
utilizing hardware-aware pruning, knowledge distillation, quantization, and our
own Transformer inference runtime engine with optimized kernels for sparse and
quantized operators. We demonstrate the efficiency of our pipeline by creating
a Fast DistilBERT model showing minimal accuracy loss on the question-answering
SQuADv1.1 benchmark, and throughput results under typical production
constraints and environments. Our results outperform existing state-of-the-art
Neural Magic's DeepSparse runtime performance by up to 50% and up to 4.1x
performance speedup over ONNX Runtime. Source code is publicly available at
https://github.com/intel/intel-extension-for-transformers.
