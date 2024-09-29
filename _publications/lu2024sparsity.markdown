---
layout: publication
title: SPP Sparsity45;preserved Parameter45;efficient Fine45;tuning For Large Language Models
authors: Lu Xudong, Zhou Aojun, Xu Yuhui, Zhang Renrui, Gao Peng, Li Hongsheng
conference: "Arxiv"
year: 2024
bibkey: lu2024sparsity
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.16057"}
  - {name: "Code", url: "https://github.com/Lucky&#45;Lance/SPP"}
tags: ['Efficiency And Optimization', 'Has Code', 'Merging', 'Pruning', 'Training Techniques']
---
Large Language Models (LLMs) have become pivotal in advancing the field of artificial intelligence yet their immense sizes pose significant challenges for both fine45;tuning and deployment. Current post45;training pruning methods while reducing the sizes of LLMs often fail to maintain their original performance. To address these challenges this paper introduces SPP a Sparsity45;Preserved Parameter45;efficient fine45;tuning method. Different from existing post45;training pruning approaches that struggle with performance retention SPP proposes to employ lightweight learnable column and row matrices to optimize sparse LLM weights keeping the structure and sparsity of pruned pre45;trained models intact. By element45;wise multiplication and residual addition SPP ensures the consistency of model sparsity pattern and ratio during both training and weight45;merging processes. We demonstrate the effectiveness of SPP by applying it to the LLaMA and LLaMA45;2 model families with recent post45;training pruning methods. Our results show that SPP significantly enhances the performance of models with different sparsity patterns (i.e. unstructured and NM sparsity) especially for those with high sparsity ratios (e.g. 7537;) making it a promising solution for the efficient fine45;tuning of sparse LLMs. Code will be made available at https://github.com/Lucky&#45;Lance/SPP.
