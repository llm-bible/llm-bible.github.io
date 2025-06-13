---
layout: publication
title: 'Seeing And Reasoning With Confidence: Supercharging Multimodal Llms With An Uncertainty-aware Agentic Framework'
authors: Zhuo Zhi, Chen Feng, Adam Daneshmend, Mine Orlu, Andreas Demosthenous, Lu Yin, Da Li, Ziquan Liu, Miguel R. D. Rodrigues
conference: "Arxiv"
year: 2025
bibkey: zhi2025seeing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.08308"}
tags: ['Fine-Tuning', 'Agentic', 'Tools', 'Applications', 'RAG', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Multimodal large language models (MLLMs) show promise in tasks like visual
question answering (VQA) but still face challenges in multimodal reasoning.
Recent works adapt agentic frameworks or chain-of-thought (CoT) reasoning to
improve performance. However, CoT-based multimodal reasoning often demands
costly data annotation and fine-tuning, while agentic approaches relying on
external tools risk introducing unreliable output from these tools. In this
paper, we propose Seeing and Reasoning with Confidence (SRICE), a training-free
multimodal reasoning framework that integrates external vision models with
uncertainty quantification (UQ) into an MLLM to address these challenges.
Specifically, SRICE guides the inference process by allowing MLLM to
autonomously select regions of interest through multi-stage interactions with
the help of external tools. We propose to use a conformal prediction-based
approach to calibrate the output of external tools and select the optimal tool
by estimating the uncertainty of an MLLM's output. Our experiment shows that
the average improvement of SRICE over the base MLLM is 4.6% on five datasets
and the performance on some datasets even outperforms fine-tuning-based
methods, revealing the significance of ensuring reliable tool use in an MLLM
agent.
