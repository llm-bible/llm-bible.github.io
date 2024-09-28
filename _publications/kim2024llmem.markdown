---
layout: publication
title: LLMem Estimating GPU Memory Usage for Fine-Tuning Pre-Trained LLMs
authors: Kim Taeho, Wang Yanming, Chaturvedi Vatshank, Gupta Lokesh, Kim Seyeon, Kwon Yongin, Ha Sangtae
conference: "Arxiv"
year: 2024
bibkey: kim2024llmem
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.10933"}
tags: ['Pretraining Methods', 'Transformer', 'Arxiv']
---
Fine-tuning pre-trained large language models (LLMs) with limited hardware presents challenges due to GPU memory constraints. Various distributed fine-tuning methods have been proposed to alleviate memory constraints on GPU. However determining the most effective method for achieving rapid fine-tuning while preventing GPU out-of-memory issues in a given environment remains unclear. To address this challenge we introduce LLMem a solution that estimates the GPU memory consumption when applying distributed fine-tuning methods across multiple GPUs and identifies the optimal method. We conduct GPU memory usage estimation prior to fine-tuning leveraging the fundamental structure of transformer-based decoder models and the memory usage distribution of each method. Experimental results show that LLMem accurately estimates peak GPU memory usage on a single GPU with error rates of up to 1.6. Additionally it shows an average error rate of 3.0 when applying distributed fine-tuning methods to LLMs with more than a billion parameters on multi-GPU setups.
