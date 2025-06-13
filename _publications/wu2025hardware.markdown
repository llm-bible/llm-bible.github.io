---
layout: publication
title: 'Halora: Hardware-aware Low-rank Adaptation For Large Language Models Based On Hybrid Compute-in-memory Architecture'
authors: Taiqiang Wu, Chenchen Ding, Wenyong Zhou, Yuxin Cheng, Xincheng Feng, Shuqi Wang, Chufan Shi, Zhengwu Liu, Ngai Wong
conference: "Arxiv"
year: 2025
bibkey: wu2025hardware
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.19747'}
tags: ['RAG', 'Security', 'Training Techniques', 'Model Architecture', 'Fine-Tuning']
---
Low-rank adaptation (LoRA) is a predominant parameter-efficient finetuning
method to adapt large language models (LLMs) for downstream tasks. In this
paper, we first propose to deploy the LoRA-finetuned LLMs on the hybrid
compute-in-memory (CIM) architecture (i.e., pretrained weights onto RRAM and
LoRA onto SRAM). To address performance degradation from RRAM's inherent noise,
we design a novel Hardware-aware Low-rank Adaption (HaLoRA) method, aiming to
train a LoRA branch that is both robust and accurate by aligning the training
objectives under both ideal and noisy conditions. Experiments finetuning LLaMA
3.2 1B and 3B demonstrate HaLoRA's effectiveness across multiple reasoning
tasks, achieving up to 22.7 improvement in average score while maintaining
robustness at various noise levels.
