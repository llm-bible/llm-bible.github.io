---
layout: publication
title: 'Llama-moe: Building Mixture-of-experts From Llama With Continual Pre-training'
authors: Zhu Tong, Qu Xiaoye, Dong Daize, Ruan Jiacheng, Tong Jingqi, He Conghui, Cheng Yu
conference: "Arxiv"
year: 2024
bibkey: zhu2024llama
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16554"}
  - {name: "Code", url: "https://github.com/pjlab-sys4nlp/llama-moe"}
tags: ['Has Code', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
'Mixture-of-Experts (MoE) has gained increasing popularity as a promising framework for scaling up large language models (LLMs). However, training MoE from scratch in a large-scale setting still suffers from data-hungry and instability problems. Motivated by this limit, we investigate building MoE models from existing dense large language models. Specifically, based on the well-known LLaMA-2 7B model, we obtain an MoE model by: (1) Expert Construction, which partitions the parameters of original Feed-Forward Networks (FFNs) into multiple experts; (2) Continual Pre-training, which further trains the transformed MoE model and additional gate networks. In this paper, we comprehensively explore different methods for expert construction and various data sampling strategies for continual pre-training. After these stages, our LLaMA-MoE models could maintain language abilities and route the input tokens to specific experts with part of the parameters activated. Empirically, by training 200B tokens, LLaMA-MoE-3.5B models significantly outperform dense models that contain similar activation parameters. The source codes and models are available at https://github.com/pjlab-sys4nlp/llama-moe .'
