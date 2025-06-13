---
layout: publication
title: 'Principled Understanding Of Generalization For Generative Transformer Models In Arithmetic Reasoning Tasks'
authors: Xingcheng Xu, Zibo Zhao, Haipeng Zhang, Yanqing Yang
conference: "Arxiv"
year: 2024
bibkey: xu2024principled
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.17963'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'GPT', 'Tools', 'Pretraining Methods']
---
Transformer-based models excel in various tasks but their generalization capabilities, especially in arithmetic reasoning, remain incompletely understood. Arithmetic tasks provide a controlled framework to explore these capabilities, yet performance anomalies persist, such as inconsistent effectiveness in multiplication and erratic generalization in modular addition (e.g., modulo 100 vs. 101). This paper develops a unified theoretical framework for understanding the generalization behaviors of transformers in arithmetic tasks, focusing on length generalization. Through detailed analysis of addition, multiplication, and modular operations, we reveal that translation invariance in addition aligns with relative positional encoding for robust generalization, while base mismatch in modular operations disrupts this alignment. Experiments across GPT-family models validate our framework, confirming its ability to predict generalization behaviors. Our work highlights the importance of task structure and training data distribution for achieving data-efficient and structure-aware training, providing a systematic approach to understanding of length generalization in transformers.
