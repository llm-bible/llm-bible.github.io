---
layout: publication
title: 'Can Post-training Quantization Benefit From An Additional Qlora Integration?'
authors: Xiliang Zhu, Elena Khasanova, Cheng Chen
conference: "Arxiv"
year: 2025
bibkey: zhu2025can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.10202"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Quantization']
---
Large language models (LLMs) have transformed natural language processing but
pose significant challenges for real-world deployment. These models necessitate
considerable computing resources, which can be costly and frequently
unavailable. Model compression techniques such as quantization are often
leveraged to alleviate resource demand, but they may have a negative impact on
the generation quality. In this study, we explore the integration of 4-bit
Post-training Quantization (PTQ) with QLoRA to address these issues. We
demonstrate through extensive experiments that this integration outperforms
standard PTQ, and in some cases even 16-bit full-parameter fine-tuning on LLMs,
validated across proprietary and public datasets with different quantization
algorithms. The results demonstrate the efficacy of PTQ-QLoRA integration,
offering a viable solution for deploying powerful LLMs in resource-constrained
environments without compromising on performance.
