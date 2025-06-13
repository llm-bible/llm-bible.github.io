---
layout: publication
title: 'DLP: Dynamic Layerwise Pruning In Large Language Models'
authors: Yuli Chen, Bo Cheng, Jiale Han, Yingying Zhang, Yingting Li, Shuhao Zhang
conference: "Arxiv"
year: 2025
bibkey: chen2025dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.23807"}
  - {name: "Code", url: "https://github.com/ironartisan/DLP"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'RAG', 'Pruning', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Pruning has recently been widely adopted to reduce the parameter scale and improve the inference efficiency of Large Language Models (LLMs). Mainstream pruning techniques often rely on uniform layerwise pruning strategies, which can lead to severe performance degradation at high sparsity levels. Recognizing the varying contributions of different layers in LLMs, recent studies have shifted their focus toward non-uniform layerwise pruning. However, these approaches often rely on pre-defined values, which can result in suboptimal performance. To overcome these limitations, we propose a novel method called Dynamic Layerwise Pruning (DLP). This approach adaptively determines the relative importance of each layer by integrating model weights with input activation information, assigning pruning rates accordingly. Experimental results show that DLP effectively preserves model performance at high sparsity levels across multiple LLMs. Specifically, at 70% sparsity, DLP reduces the perplexity of LLaMA2-7B by 7.79 and improves the average accuracy by 2.7% compared to state-of-the-art methods. Moreover, DLP is compatible with various existing LLM compression techniques and can be seamlessly integrated into Parameter-Efficient Fine-Tuning (PEFT). We release the code at https://github.com/ironartisan/DLP to facilitate future research.
