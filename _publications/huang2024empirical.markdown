---
layout: publication
title: An Empirical Study Of Llama3 Quantization From Llms To Mllms
authors: Huang Wei, Zheng Xingyu, Ma Xudong, Qin Haotong, Lv Chengtao, Chen Hong, Luo Jie, Qi Xiaojuan, Liu Xianglong, Magno Michele
conference: "Arxiv"
year: 2024
bibkey: huang2024empirical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.14047"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Multimodal Models', 'Quantization', 'Reinforcement Learning', 'Training Techniques']
---
The LLaMA family has become one of the most powerful open45;source Large Language Models (LLMs) and the popular LLM backbones of Multimodal Large Language Models (MLLMs) widely applied in Computer Vision (CV) and Natural Language Understanding (NLU) tasks. Notably LLaMA3 models have recently been released and achieve impressive performance across various with super45;large scale pre45;training on over 15T tokens of data. Given the wide application of low45;bit quantization for LLMs in resource45;limited scenarios we explore LLaMA3s capabilities when quantized to low bit45;width. This exploration can potentially unveil new insights and challenges for low45;bit quantization of LLaMA3 and other forthcoming LLMs especially in addressing performance degradation problems that suffer in LLM compression. Specifically we comprehensively evaluate the 10 existing post45;training quantization and LoRA45;finetuning methods of LLaMA3 on 145;8 bits and diverse datasets to reveal LLaMA3s low45;bit quantization performance. To uncover the capabilities of low45;bit quantized MLLM we assessed the performance of the LLaMA345;based LLaVA45;Next45;8B model under 245;4 ultra45;low bits with post45;training quantization methods. Our experimental results indicate that LLaMA3 still suffers non45;negligent degradation in linguistic and visual contexts particularly under ultra45;low bit widths. This highlights the significant performance gap under low bit45;width that needs to be bridged in future developments. We expect that this empirical study will prove valuable in advancing future models driving LLMs and MLLMs to achieve higher accuracy at lower bit to enhance practicality.
