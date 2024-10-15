---
layout: publication
title: 'First Activations Matter: Training-free Methods For Dynamic Activation In Large Language Models'
authors: Ma Chi, Huang Mincong, Zhang Ying, Wang Chao, Wang Yujie, Yu Lei, Liu Chuan, Lin Wei
conference: "Arxiv"
year: 2024
bibkey: ma2024first
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11393"}
tags: ['Efficiency And Optimization', 'Model Architecture', 'RAG', 'Training Techniques', 'Uncategorized']
---
Dynamic activation (DA) techniques, such as DejaVu and MoEfication, have
demonstrated their potential to significantly enhance the inference efficiency
of large language models (LLMs). However, these techniques often rely on ReLU
activation functions or require additional parameters and training to maintain
performance. This paper introduces a training-free Threshold-based Dynamic
Activation(TDA) method that leverage sequence information to exploit the
inherent sparsity of models across various architectures. This method is
designed to accelerate generation speed by 18-25% without significantly
compromising task performance, thereby addressing the limitations of existing
DA techniques. Moreover, we delve into the root causes of LLM sparsity and
theoretically analyze two of its critical features: history-related activation
uncertainty and semantic-irrelevant activation inertia. Our comprehensive
analyses not only provide a robust theoretical foundation for DA methods but
also offer valuable insights to guide future research in optimizing LLMs for
greater efficiency and effectiveness.
