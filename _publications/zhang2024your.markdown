---
layout: publication
title: 'Lighttransfer: Your Long-context LLM Is Secretly A Hybrid Model With Effortless Adaptation'
authors: Xuan Zhang, Fengzhuo Zhang, Cunxiao Du, Chao Du, Tianyu Pang, Wei Gao, Min Lin
conference: "Arxiv"
year: 2024
bibkey: zhang2024your
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.13846'}
tags: ['Attention Mechanism', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Scaling language models to handle longer contexts introduces substantial
memory challenges due to the growing cost of key-value (KV) caches. Motivated
by the efficiency gains of hybrid models and the broad availability of
pretrained large transformer backbones, we explore transitioning transformer
models into hybrid architectures for a more efficient generation. In this work,
we propose LightTransfer, a lightweight method that transforms models such as
LLaMA into hybrid variants. Our approach identifies lazy layers -- those
focusing on recent or initial tokens -- and replaces their full attention with
streaming attention. This transformation can be performed without any training
for long-context understanding tasks or with minimal fine-tuning for o1-like
long reasoning generation tasks that require stronger reasoning capabilities.
Experiments across diverse benchmarks and models (e.g., LLaMA, Mistral,
QwQ-STILL) demonstrate that, even when half of the layers are identified as
lazy, LightTransfer achieves up to 2.17\\(\times\\) throughput improvement with
minimal performance loss (\\(<1.5%\\) on LongBench) and achieves 53.3% on math
benchmark AIME24 of advanced o1-like long reasoning model QwQ-STILL.
