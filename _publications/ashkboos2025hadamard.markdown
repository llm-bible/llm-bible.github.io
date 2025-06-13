---
layout: publication
title: 'HALO: Hadamard-assisted Lower-precision Optimization For Llms'
authors: Saleh Ashkboos, Mahdi Nikdan, Soroush Tabesh, Roberto L. Castro, Torsten Hoefler, Dan Alistarh
conference: "Arxiv"
year: 2025
bibkey: ashkboos2025hadamard
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.02625'}
  - {name: "Code", url: 'https://github.com/IST-DASLab/HALO'}
tags: ['Has Code', 'Transformer', 'Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Quantization', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Quantized training of Large Language Models (LLMs) remains an open challenge,
as maintaining accuracy while performing all matrix multiplications in low
precision has proven difficult. This is particularly the case when fine-tuning
pre-trained models, which can have large weight and activation outlier values
that make lower-precision optimization difficult. To address this, we present
HALO, a novel quantization-aware training approach for Transformers that
enables accurate and efficient low-precision training by combining 1) strategic
placement of Hadamard rotations in both forward and backward passes, which
mitigate outliers, 2) high-performance kernel support, and 3) FSDP integration
for low-precision communication. Our approach ensures that all large matrix
multiplications during the forward and backward passes are executed in lower
precision. Applied to LLAMA-family models, HALO achieves
near-full-precision-equivalent results during fine-tuning on various tasks,
while delivering up to 1.41x end-to-end speedup for full fine-tuning on RTX
4090 GPUs. HALO efficiently supports both standard and parameterefficient
fine-tuning (PEFT). Our results demonstrate the first practical approach to
fully quantized LLM fine-tuning that maintains accuracy in 8-bit precision,
while delivering performance benefits. Code is available at
\url\{https://github.com/IST-DASLab/HALO\}.
