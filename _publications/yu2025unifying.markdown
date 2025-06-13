---
layout: publication
title: 'Cafe: Unifying Representation And Generation With Contrastive-autoregressive Finetuning'
authors: Hao Yu, Zhuokai Zhao, Shen Yan, Lukasz Korycki, Jianyu Wang, Baosheng He, Jiayi Liu, Lizhu Zhang, Xiangjun Fan, Hanchao Yu
conference: "Arxiv"
year: 2025
bibkey: yu2025unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.19900"}
tags: ['Multimodal Models', 'Training Techniques', 'Tools', 'Language Modeling', 'GPT', 'Pretraining Methods', 'Fine-Tuning']
---
The rapid advancement of large vision-language models (LVLMs) has driven
significant progress in multimodal tasks, enabling models to interpret, reason,
and generate outputs across both visual and textual domains. While excelling in
generative tasks, existing LVLMs often face limitations in tasks requiring
high-fidelity representation learning, such as generating image or text
embeddings for retrieval. Recent work has proposed finetuning LVLMs for
representational learning, but the fine-tuned model often loses its generative
capabilities due to the representational learning training paradigm. To address
this trade-off, we introduce CAFe, a contrastive-autoregressive fine-tuning
framework that enhances LVLMs for both representation and generative tasks. By
integrating a contrastive objective with autoregressive language modeling, our
approach unifies these traditionally separate tasks, achieving state-of-the-art
results in both multimodal retrieval and multimodal generative benchmarks,
including object hallucination (OH) mitigation. CAFe establishes a novel
framework that synergizes embedding and generative functionalities in a single
model, setting a foundation for future multimodal models that excel in both
retrieval precision and coherent output generation.
