---
layout: publication
title: 'Do Emergent Abilities Exist In Quantized Large Language Models: An Empirical Study'
authors: Peiyu Liu, Zikang Liu, Ze-feng Gao, Dawei Gao, Wayne Xin Zhao, Yaliang Li, Bolin Ding, Ji-rong Wen
conference: "Arxiv"
year: 2023
bibkey: liu2023do
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2307.08072'}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Quantization', 'Fine-Tuning', 'Prompting', 'In-Context Learning', 'Pretraining Methods']
---
Despite the superior performance, Large Language Models~(LLMs) require
significant computational resources for deployment and use. To overcome this
issue, quantization methods have been widely applied to reduce the memory
footprint of LLMs as well as increasing the inference rate. However, a major
challenge is that low-bit quantization methods often lead to performance
degradation. It is important to understand how quantization impacts the
capacity of LLMs. Different from previous studies focused on overall
performance, this work aims to investigate the impact of quantization on
*emergent abilities*, which are important characteristics that distinguish
LLMs from small language models. Specially, we examine the abilities of
in-context learning, chain-of-thought reasoning, and instruction-following in
quantized LLMs. Our empirical experiments show that these emergent abilities
still exist in 4-bit quantization models, while 2-bit models encounter severe
performance degradation on the test of these abilities. To improve the
performance of low-bit models, we conduct two special experiments: (1)
fine-gained impact analysis that studies which components (or substructures)
are more sensitive to quantization, and (2) performance compensation through
model fine-tuning. Our work derives a series of important findings to
understand the impact of quantization on emergent abilities, and sheds lights
on the possibilities of extremely low-bit quantization for LLMs.
