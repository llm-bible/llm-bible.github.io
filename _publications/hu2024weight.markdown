---
layout: publication
title: 'Dota: Weight-decomposed Tensor Adaptation For Large Language Models'
authors: Xiaolin Hu, Xiang Cheng, Peiyu Liu, Wei Liu, Jian Luan, Bin Wang, Yong Liu
conference: "Arxiv"
year: 2024
bibkey: hu2024weight
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.20891"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Quantization', 'Pretraining Methods', 'Fine-Tuning']
---
Low-rank adaptation (LoRA) reduces the computational and memory demands of
fine-tuning large language models (LLMs) by approximating updates with low-rank
matrices. However, low-rank approximation in two-dimensional space fails to
capture high-dimensional structures within the target matrix. Recently, tensor
decomposition methods have been explored for fine-tuning LLMs, leveraging their
ability to extract structured information. Yet, these approaches primarily rely
on random initialization, and the impact of initialization on tensor adaptation
remains underexplored. In this paper, we reveal that random initialization
significantly diverges from the validation loss achieved by full fine-tuning.
To address this, we propose Weight-Decomposed Tensor Adaptation (DoTA), which
leverages the Matrix Product Operator (MPO) decomposition of pre-trained
weights for effective initialization in fine-tuning LLMs. Additionally, we
introduce QDoTA, a quantized version of DoTA designed for 4-bit quantization.
Experiments on commonsense and arithmetic reasoning tasks show that DoTA
outperforms random initialization methods with fewer parameters. QDoTA further
reduces memory consumption and achieves comparable performance to DoTA on
commonsense reasoning tasks. We will release our code to support future
research.
