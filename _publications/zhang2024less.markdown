---
layout: publication
title: 'Less Is More: Extreme Gradient Boost Rank-1 Adaption For Efficient Finetuning Of Llms'
authors: Yifei Zhang, Hao Zhu, Aiwei Liu, Han Yu, Piotr Koniusz, Irwin King
conference: "Arxiv"
year: 2024
bibkey: zhang2024less
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.19694"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning']
---
Fine-tuning Large Language Models (LLMs) has become a crucial technique for
adapting pre-trained models to downstream tasks. However, the enormous size of
LLMs poses significant challenges in terms of computational complexity and
resource requirements. Low-Rank Adaptation (LoRA) has emerged as a promising
solution. However, there exists a gap between the practical performance of
low-rank adaptations and its theoretical optimum. In this work, we propose
eXtreme Gradient Boosting LoRA (XGBLoRA), a novel framework that bridges this
gap by leveraging the power of ensemble learning. Inspired by gradient
boosting, XGBLoRA iteratively learns and merges a sequence of LoRA adaptations
to refine model predictions. It achieves better performance than the standard
LoRA, while enjoying the computational efficiency of rank-1 adaptations. We
provide theoretical analysis to show the convergence and optimality of our
approach, and conduct extensive experiments on a range of natural language
processing tasks. The results demonstrate that XGBLoRA consistently outperforms
standard LoRA and achieves performance comparable to full fine-tuning with
significantly fewer trainable parameters. This work advances
parameter-efficient fine-tuning for LLMs, and offers a promising solution for
adapting LLMs to downstream tasks while optimizing performance and efficiency.
