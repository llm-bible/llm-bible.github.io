---
layout: publication
title: 'V-seek: Accelerating LLM Reasoning On Open-hardware Server-class RISC-V Platforms'
authors: Javier J. Poveda Rodrigo, Mohamed Amine Ahmdi, Alessio Burrello, Daniele Jahier Pagliari, Luca Benini
conference: "Arxiv"
year: 2025
bibkey: rodrigo2025v
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17422"}
tags: ['Prompting', 'Merging', 'Tools']
---
The recent exponential growth of Large Language Models (LLMs) has relied on
GPU-based systems. However, CPUs are emerging as a flexible and lower-cost
alternative, especially when targeting inference and reasoning workloads.
RISC-V is rapidly gaining traction in this area, given its open and
vendor-neutral ISA. However, the RISC-V hardware for LLM workloads and the
corresponding software ecosystem are not fully mature and streamlined, given
the requirement of domain-specific tuning. This paper aims at filling this gap,
focusing on optimizing LLM inference on the Sophon SG2042, the first
commercially available many-core RISC-V CPU with vector processing
capabilities.
  On two recent state-of-the-art LLMs optimized for reasoning, DeepSeek R1
Distill Llama 8B and DeepSeek R1 Distill QWEN 14B, we achieve 4.32/2.29 token/s
for token generation and 6.54/3.68 token/s for prompt processing, with a speed
up of up 2.9x/3.0x compared to our baseline.
