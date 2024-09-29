---
layout: publication
title: MINI45;SEQUENCE TRANSFORMER Optimizing Intermediate Memory For Long Sequences Training
authors: Luo Cheng, Zhao Jiawei, Chen Zhuoming, Chen Beidi, Anandkumar Anima
conference: "Arxiv"
year: 2024
bibkey: luo2024mini
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15892"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
We introduce Mini45;Sequence Transformer (MsT) a simple and effective methodology for highly efficient and accurate LLM training with extremely long sequences. MsT partitions input sequences and iteratively processes mini45;sequences to reduce intermediate memory usage. Integrated with activation recomputation it enables significant memory savings in both forward and backward passes. In experiments with the Llama345;8B model with MsT we measure no degradation in throughput or convergence even with 12x longer sequences than standard implementations due to our careful memory optimizations. MsT is fully general implementation45;agnostic and requires minimal code changes to integrate with existing LLM training frameworks.
