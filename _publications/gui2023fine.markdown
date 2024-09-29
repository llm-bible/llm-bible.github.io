---
layout: publication
title: SPT\: Fine-tuning Transformer-based Language Models Efficiently With Sparsification
authors: Gui Yuntao, Yan Xiao, Yin Peiqi, Yang Han, Cheng James
conference: "Arxiv"
year: 2023
bibkey: gui2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10365"}
tags: ['Attention Mechanism', 'BERT', 'Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Pruning', 'Quantization', 'Training Techniques', 'Transformer']
---
Transformer-based large language models (e.g. BERT and GPT) achieve great success and fine-tuning which tunes a pre-trained model on a task-specific dataset is the standard practice to utilize these models for downstream tasks. However Transformer fine-tuning has long running time and high memory consumption due to the large size of the models. We propose the SPT system to fine-tune Transformer-based models efficiently by introducing sparsity. We observe that the memory consumption of Transformer mainly comes from storing attention weights for multi-head attention (MHA) and the majority of running time is spent on feed-forward network (FFN). Thus we design the sparse MHA module which computes and stores only large attention weights to reduce memory consumption and the routed FFN module which dynamically activates a subset of model parameters for each token to reduce computation cost. We implement SPT on PyTorch and customize CUDA kernels to run sparse MHA and routed FFN efficiently. Specifically we use product quantization to identify the large attention weights and compute attention via sparse matrix multiplication for sparse MHA. For routed FFN we batch the tokens according to their activated model parameters for efficient computation. We conduct extensive experiments to evaluate SPT on various model configurations. The results show that SPT consistently outperforms well-optimized baselines reducing the peak memory consumption by up to 5037; and accelerating fine-tuning by up to 2.2x.
