---
layout: publication
title: 'Lowra: Accurate And Efficient Lora Fine-tuning Of Llms Under 2 Bits'
authors: Zikai Zhou, Qizheng Zhang, Hermann Kumbong, Kunle Olukotun
conference: "Arxiv"
year: 2025
bibkey: zhou2025accurate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.08141"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'RAG', 'Quantization', 'Pretraining Methods', 'Fine-Tuning']
---
Fine-tuning large language models (LLMs) is increasingly costly as models
scale to hundreds of billions of parameters, and even parameter-efficient
fine-tuning (PEFT) methods like LoRA remain resource-intensive. We introduce
LowRA, the first framework to enable LoRA fine-tuning below 2 bits per
parameter with minimal performance loss. LowRA optimizes fine-grained
quantization - mapping, threshold selection, and precision assignment - while
leveraging efficient CUDA kernels for scalable deployment. Extensive
evaluations across 4 LLMs and 4 datasets show that LowRA achieves a superior
performance-precision trade-off above 2 bits and remains accurate down to 1.15
bits, reducing memory usage by up to 50%. Our results highlight the potential
of ultra-low-bit LoRA fine-tuning for resource-constrained environments.
