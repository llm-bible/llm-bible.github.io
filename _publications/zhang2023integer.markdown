---
layout: publication
title: 'Integer Or Floating Point? New Outlooks For Low-bit Quantization On Large Language Models'
authors: Yijia Zhang, Lingran Zhao, Shijie Cao, Wenqiang Wang, Ting Cao, Fan Yang, Mao Yang, Shanghang Zhang, Ningyi Xu
conference: "Arxiv"
year: 2023
bibkey: zhang2023integer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.12356'}
tags: ['Efficiency and Optimization', 'GPT', 'Model Architecture', 'Training Techniques', 'Quantization', 'Merging', 'Reinforcement Learning']
---
Efficient deployment of large language models (LLMs) necessitates low-bit
quantization to minimize model size and inference cost. While low-bit integer
formats (e.g., INT8/INT4) have been the conventional choice, emerging low-bit
floating-point formats (e.g., FP8/FP4) offer a compelling alternative and are
gaining support from cutting-edge hardware, such as NVIDIA's H100 GPU. However,
the superiority of low-bit INT versus FP formats for quantization on LLMs
remains unclear. In this study, we conduct a comparative analysis of INT and FP
quantization with the same bit-width, revealing that the optimal quantization
format varies across different layers due to the complexity and diversity of
tensor distribution. Consequently, we advocate the Mixture of Formats
Quantization (MoFQ), which selects the optimal format on a layer-wise basis.
This simple yet effective approach achieves state-of-the-art results in both
weight-only (W-only) and weight-activation (WA) post-training quantization
scenarios when tested on LLaMA across various tasks. In 4-bit W-only
quantization, MoFQ surpasses GPTQ without complex hyperparameter tuning and
with an order of magnitude faster quantization speed. While in 8-bit WA
quantization, MoFQ significantly outperforms INT/FP-only methods, achieving
performance close to the full precision model. Notably, MoFQ incurs no hardware
overhead compared to INT/FP-only quantization, as the bit-width remains
unchanged.
