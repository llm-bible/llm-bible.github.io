---
layout: publication
title: 'On-device Qwen2.5: Efficient LLM Inference With Model Compression And Hardware Acceleration'
authors: Maoyang Xiang, Ramesh Fernando, Bo Wang
conference: "Arxiv"
year: 2025
bibkey: xiang2025efficient
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.17376'}
tags: ['Transformer', 'RAG', 'Efficiency and Optimization', 'Model Architecture', 'Tools', 'Quantization', 'Pretraining Methods']
---
Transformer-based Large Language Models (LLMs) have significantly advanced AI
capabilities but pose considerable challenges for deployment on edge devices
due to high computational demands, memory bandwidth constraints, and energy
consumption. This paper addresses these challenges by presenting an efficient
framework for deploying the Qwen2.5-0.5B model on the Xilinx Kria KV260 edge
platform, a heterogeneous system integrating an ARM Cortex-A53 CPU with
reconfigurable FPGA logic. Leveraging Activation-aware Weight Quantization
(AWQ) with FPGA-accelerated execution pipelines, the proposed approach enhances
both model compression rate and system throughput. Additionally, we propose a
hybrid execution strategy that intelligently offloads compute-intensive
operations to the FPGA while utilizing the CPU for lighter tasks, effectively
balancing the computational workload and maximizing overall performance. Our
framework achieves a model compression rate of 55.08% compared to the original
model and produces output at a rate of 5.1 tokens per second, outperforming the
baseline performance of 2.8 tokens per second.
