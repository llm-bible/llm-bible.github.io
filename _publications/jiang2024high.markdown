---
layout: publication
title: Mora&#58; High-rank Updating For Parameter-efficient Fine-tuning
authors: Jiang Ting, Huang Shaohan, Luo Shengyue, Zhang Zihan, Huang Haizhen, Wei Furu, Deng Weiwei, Sun Feng, Zhang Qi, Wang Deqing, Zhuang Fuzhen
conference: "Arxiv"
year: 2024
bibkey: jiang2024high
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.12130"}
tags: ['Fine Tuning', 'Pretraining Methods', 'Training Techniques']
---
Low-rank adaptation is a popular parameter-efficient fine-tuning method for large language models. In this paper we analyze the impact of low-rank updating as implemented in LoRA. Our findings suggest that the low-rank updating mechanism may limit the ability of LLMs to effectively learn and memorize new knowledge. Inspired by this observation we propose a new method called MoRA which employs a square matrix to achieve high-rank updating while maintaining the same number of trainable parameters. To achieve it we introduce the corresponding non-parameter operators to reduce the input dimension and increase the output dimension for the square matrix. Furthermore these operators ensure that the weight can be merged back into LLMs which makes our method can be deployed like LoRA. We perform a comprehensive evaluation of our method across five tasks instruction tuning mathematical reasoning continual pretraining memory and pretraining. Our method outperforms LoRA on memory-intensive tasks and achieves comparable performance on other tasks.
