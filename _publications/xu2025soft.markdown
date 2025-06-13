---
layout: publication
title: 'Softcot: Soft Chain-of-thought For Efficient Reasoning With Llms'
authors: Yige Xu, Xu Guo, Zhiwei Zeng, Chunyan Miao
conference: "Arxiv"
year: 2025
bibkey: xu2025soft
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12134"}
  - {name: "Code", url: "https://github.com/xuyige/SoftCoT"}
tags: ['Fine-Tuning', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Chain-of-Thought (CoT) reasoning enables Large Language Models (LLMs) to solve complex reasoning tasks by generating intermediate reasoning steps. However, most existing approaches focus on hard token decoding, which constrains reasoning within the discrete vocabulary space and may not always be optimal. While recent efforts explore continuous-space reasoning, they often require full-model fine-tuning and suffer from catastrophic forgetting, limiting their applicability to state-of-the-art LLMs that already perform well in zero-shot settings with a proper instruction. To address this challenge, we propose a novel approach for continuous-space reasoning that does not require modifying the LLM. Specifically, we employ a lightweight fixed assistant model to speculatively generate instance-specific soft thought tokens as the initial chain of thoughts, which are then mapped into the LLM's representation space via a trainable projection module. Experimental results on five reasoning benchmarks demonstrate that our method enhances LLM reasoning performance through supervised, parameter-efficient fine-tuning. Source code is available at https://github.com/xuyige/SoftCoT.
