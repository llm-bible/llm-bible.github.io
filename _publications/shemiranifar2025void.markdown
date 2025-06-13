---
layout: publication
title: 'Void In Language Models'
authors: Mani Shemiranifar
conference: "Arxiv"
year: 2025
bibkey: shemiranifar2025void
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14467"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Prompting']
---
Despite advances in transformer-based language models (LMs), a fundamental question remains largely unanswered: Are all layers activated during inference? We investigate this question by detecting unactivated layers (which we refer to as Voids) using a non-trainable and parameter-free adaptive computation method called L2 Adaptive Computation (LAC). We adapt LAC from its original efficiency-focused application to trace activated layers during inference. This method monitors changes in the L2-norm of activations to identify voids. We analyze layer activation in instruction-tuned LMs across two phases: Prompt Processing (PP), where we trace activated layers for each token in the input prompts, and Response Generation (RG), where we trace activated layers for each generated token. We further demonstrate that distinct layers are activated during these two phases. To show the effectiveness of our method, we evaluated three distinct instruction-tuned LMs from the Llama, Mistral, and Qwen families on three benchmarks: MMLU, GPQA Diamond, and BoolQ. For example, on MMLU with a zero-shot setting, skipping voids in Qwen2.5-7B-Instruct resulted in an improvement from 69.24 to 71.29 while the model uses only 30% of the layers. Similarly, Mistral-7B-Instruct-v0.3 on GPQA Diamond improved from 13.88 to 18.36 when using 70% of the layers during both the PP and RG phases. These results show that not all layers contribute equally during inference, and that selectively skipping most of them can improve the performance of models on certain tasks.
