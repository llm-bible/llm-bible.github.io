---
layout: publication
title: An Empirical Study of LLaMA3 Quantization From LLMs to MLLMs
authors: Huang Wei, Zheng Xingyu, Ma Xudong, Qin Haotong, Lv Chengtao, Chen Hong, Luo Jie, Qi Xiaojuan, Liu Xianglong, Magno Michele
conference: "Arxiv"
year: 2024
bibkey: huang2024empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14047"}
tags: ['ARXIV', 'Efficiency And Optimization', 'LLM', 'Quantization']
---
The LLaMA family has become one of the most powerful open-source Large Language Models (LLMs) and the popular LLM backbones of Multimodal Large Language Models (MLLMs) widely applied in Computer Vision (CV) and Natural Language Understanding (NLU) tasks. Notably LLaMA3 models have recently been released and achieve impressive performance across various with super-large scale pre-training on over 15T tokens of data. Given the wide application of low-bit quantization for LLMs in resource-limited scenarios we explore LLaMA3s capabilities when quantized to low bit-width. This exploration can potentially unveil new insights and challenges for low-bit quantization of LLaMA3 and other forthcoming LLMs especially in addressing performance degradation problems that suffer in LLM compression. Specifically we comprehensively evaluate the 10 existing post-training quantization and LoRA-finetuning methods of LLaMA3 on 1-8 bits and diverse datasets to reveal LLaMA3s low-bit quantization performance. To uncover the capabilities of low-bit quantized MLLM we assessed the performance of the LLaMA3-based LLaVA-Next-8B model under 2-4 ultra-low bits with post-training quantization methods. Our experimental results indicate that LLaMA3 still suffers non-negligent degradation in linguistic and visual contexts particularly under ultra-low bit widths. This highlights the significant performance gap under low bit-width that needs to be bridged in future developments. We expect that this empirical study will prove valuable in advancing future models driving LLMs and MLLMs to achieve higher accuracy at lower bit to enhance practicality.
