---
layout: publication
title: 'Aslora: Adaptive Sharing Low-rank Adaptation Across Layers'
authors: Junyan Hu, Xue Xiao, Mengqi Zhang, Yao Chen, Zhaochun Ren, Zhumin Chen, Pengjie Ren
conference: "Arxiv"
year: 2024
bibkey: hu2024adaptive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.10135'}
tags: ['RAG', 'Efficiency and Optimization', 'Training Techniques', 'Fine-Tuning', 'Pretraining Methods']
---
As large language models (LLMs) grow in size, traditional full fine-tuning
becomes increasingly impractical due to its high computational and storage
costs. Although popular parameter-efficient fine-tuning methods, such as LoRA,
have significantly reduced the number of tunable parameters, there is still
room for further optimization. In this work, we propose ASLoRA, a cross-layer
parameter-sharing strategy combining global sharing with partial adaptive
sharing. Specifically, we share the low-rank matrix A across all layers and
adaptively merge matrix B during training. This sharing mechanism not only
mitigates overfitting effectively but also captures inter-layer dependencies,
significantly enhancing the model's representational capability. We conduct
extensive experiments on various NLP tasks, showing that ASLoRA outperforms
LoRA while using less than 25% of the parameters, highlighting its flexibility
and superior parameter efficiency. Furthermore, in-depth analyses of the
adaptive sharing strategy confirm its significant advantages in enhancing both
model flexibility and task adaptability.
