---
layout: publication
title: SPT Fine45;tuning Transformer45;based Language Models Efficiently With Sparsification
authors: Gui Yuntao, Yan Xiao, Yin Peiqi, Yang Han, Cheng James
conference: "Arxiv"
year: 2023
bibkey: gui2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10365"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'Transformer']
---
Transformer45;based large language models (e.g. BERT and GPT) achieve great success and fine45;tuning which tunes a pre45;trained model on a task45;specific dataset is the standard practice to utilize these models for downstream tasks. However Transformer fine45;tuning has long running time and high memory consumption due to the large size of the models. We propose the SPT system to fine45;tune Transformer45;based models efficiently by introducing sparsity. We observe that the memory consumption of Transformer mainly comes from storing attention weights for multi45;head attention (MHA) and the majority of running time is spent on feed45;forward network (FFN). Thus we design the sparse MHA module which computes and stores only large attention weights to reduce memory consumption and the routed FFN module which dynamically activates a subset of model parameters for each token to reduce computation cost. We implement SPT on PyTorch and customize CUDA kernels to run sparse MHA and routed FFN efficiently. Specifically we use product quantization to identify the large attention weights and compute attention via sparse matrix multiplication for sparse MHA. For routed FFN we batch the tokens according to their activated model parameters for efficient computation. We conduct extensive experiments to evaluate SPT on various model configurations. The results show that SPT consistently outperforms well45;optimized baselines reducing the peak memory consumption by up to 5037; and accelerating fine45;tuning by up to 2.2x.
