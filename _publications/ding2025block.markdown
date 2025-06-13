---
layout: publication
title: 'Block Circulant Adapter For Large Language Models'
authors: Xinyu Ding, Meiqi Wang, Siyu Liao, Zhongfeng Wang
conference: "Arxiv"
year: 2025
bibkey: ding2025block
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00582"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques', 'Fine-Tuning']
---
Fine-tuning large language models (LLMs) is difficult due to their huge model
size. Recent Fourier domain-based methods show potential for reducing
fine-tuning costs. We propose a block circulant matrix-based fine-tuning method
with a stable training heuristic to leverage the properties of circulant
matrices and one-dimensional Fourier transforms to reduce storage and
computation costs. Experiments show that our method uses \\(14\times\\) less number
of parameters than VeRA, \\(16\times\\) smaller than LoRA and \\(32\times\\) less FLOPs
than FourierFT, while maintaining close or better task performance. Our
approach presents a promising way in frequency domain to fine-tune large models
on downstream tasks.
