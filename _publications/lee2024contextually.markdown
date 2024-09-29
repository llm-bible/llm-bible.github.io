---
layout: publication
title: CATS Contextually45;aware Thresholding For Sparsity In Large Language Models
authors: Lee Je-yong, Lee Donghyun, Zhang Genghan, Tiwari Mo, Mirhoseini Azalia
conference: "Arxiv"
year: 2024
bibkey: lee2024contextually
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.08763"}
tags: ['Applications', 'Pruning', 'Tools']
---
Large Language Models (LLMs) have dramatically advanced AI applications yet their deployment remains challenging due to their immense inference costs. Recent studies ameliorate the computational costs of LLMs by increasing their activation sparsity but suffer from significant performance degradation on downstream tasks. In this work we introduce a new framework for sparsifying the activations of base LLMs and reducing inference costs dubbed Contextually Aware Thresholding for Sparsity (CATS). CATS is relatively simple easy to implement and highly effective. At the heart of our framework is a new non45;linear activation function. We demonstrate that CATS can be applied to various base models including Mistral45;7B and Llama245;7B and outperforms existing sparsification techniques in downstream task performance. More precisely CATS45;based models often achieve downstream task performance within 145;237; of their base models without any fine45;tuning and even at activation sparsity levels of 5037;. Furthermore CATS45;based models converge faster and display better task performance than competing techniques when fine45;tuning is applied. Finally we develop a custom GPU kernel for efficient implementation of CATS that translates the activation of sparsity of CATS to real wall45;clock time speedups. Our custom kernel implementation of CATS results in a ~1537; improvement in wall45;clock inference latency of token generation on both Llama45;7B and Mistral45;7B.
