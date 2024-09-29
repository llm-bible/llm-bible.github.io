---
layout: publication
title: Ternaryllm Ternarized Large Language Model
authors: Chen Tianqi, Li Zhe, Xu Weixiang, Zhu Zeyu, Li Dong, Tian Lu, Barsoum Emad, Wang Peisong, Cheng Jian
conference: "Arxiv"
year: 2024
bibkey: chen2024ternarized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07177"}
tags: ['Applications', 'Distillation', 'Efficiency And Optimization', 'Language Modeling', 'Quantization', 'RAG']
---
Large language models (LLMs) have achieved remarkable performance on Natural Language Processing (NLP) tasks but they are hindered by high computational costs and memory requirements. Ternarization an extreme form of quantization offers a solution by reducing memory usage and enabling energy45;efficient floating45;point additions. However applying ternarization to LLMs faces challenges stemming from outliers in both weights and activations. In this work observing asymmetric outliers and non45;zero means in weights we introduce Dual Learnable Ternarization (DLT) which enables both scales and shifts to be learnable. We also propose Outlier45;Friendly Feature Knowledge Distillation (OFF) to recover the information lost in extremely low45;bit quantization. The proposed OFF can incorporate semantic information and is insensitive to outliers. At the core of OFF is maximizing the mutual information between features in ternarized and floating45;point models using cosine similarity. Extensive experiments demonstrate that our TernaryLLM surpasses previous low45;bit quantization methods on the standard text generation and zero45;shot benchmarks for different LLM families. Specifically for one of the most powerful open45;source models LLaMA45;3 our approach (W1.58A16) outperforms the previous state45;of45;the45;art method (W2A16) by 5.8 in terms of perplexity on C4 and by 8.237; in terms of average accuracy on zero45;shot tasks.
