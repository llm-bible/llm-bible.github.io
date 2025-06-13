---
layout: publication
title: 'Dissecting The Runtime Performance Of The Training, Fine-tuning, And Inference Of Large Language Models'
authors: Longteng Zhang, Xiang Liu, Zeyu Li, Xinglin Pan, Peijie Dong, Ruibo Fan, Rui Guo, Xin Wang, Qiong Luo, Shaohuai Shi, Xiaowen Chu
conference: "Arxiv"
year: 2023
bibkey: zhang2023dissecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.03687"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Quantization', 'Pretraining Methods', 'Fine-Tuning', 'Pre-Training', 'Attention Mechanism']
---
Large Language Models (LLMs) have seen great advance in both academia and
industry, and their popularity results in numerous open-source frameworks and
techniques in accelerating LLM pre-training, fine-tuning, and inference.
Training and deploying LLMs are expensive as it requires considerable computing
resources and memory, hence many efficient approaches have been developed for
improving system pipelines as well as operators. However, the runtime
performance can vary significantly across hardware and software stacks, which
makes it difficult to choose the best configuration. In this work, we aim to
benchmark the performance from both macro and micro perspectives. First, we
benchmark the end-to-end performance of pre-training, fine-tuning, and serving
LLMs in different sizes , i.e., 7, 13, and 70 billion parameters (7B, 13B, and
70B) on three 8-GPU platforms with and without individual optimization
techniques, including ZeRO, quantization, recomputation, FlashAttention. Then,
we dive deeper to provide a detailed runtime analysis of the sub-modules,
including computing and communication operators in LLMs. For end users, our
benchmark and findings help better understand different optimization
techniques, training and inference frameworks, together with hardware platforms
in choosing configurations for deploying LLMs. For researchers, our in-depth
module-wise analyses discover potential opportunities for future work to
further optimize the runtime performance of LLMs.
