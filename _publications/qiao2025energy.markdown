---
layout: publication
title: 'Tellme: An Energy-efficient Ternary LLM Accelerator For Prefilling And Decoding On Edge Fpgas'
authors: Ye Qiao, Zhiheng Chen, Yifan Zhang, Yian Wang, Sitao Huang
conference: "Arxiv"
year: 2025
bibkey: qiao2025energy
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16266"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Quantization', 'Pretraining Methods', 'Prompting', 'Attention Mechanism']
---
Deploying large language models (LLMs) on edge platforms is challenged by
their high computational and memory demands. Although recent low-bit
quantization methods (e.g., BitNet, DeepSeek) compress weights to as little as
1.58 bits with minimal accuracy loss, edge deployment is still constrained by
limited on-chip resources, power budgets, and the often-neglected latency of
the prefill phase. We present TeLLMe, the first ternary LLM accelerator for
low-power FPGAs (e.g., AMD KV260) that fully supports both prefill and
autoregressive decoding using 1.58-bit weights and 8-bit activations. Our
contributions include: (1) a table-lookup matrix engine for ternary matmul that
merges grouped activations with online precomputation to minimize resource use;
(2) a fused, bandwidth-efficient attention module featuring a reversed
reordering scheme to accelerate prefill; and (3) a tightly integrated
normalization and quantization--dequantization unit optimized for ultra-low-bit
inference. Under a 7W power budget, TeLLMe delivers up to 9 tokens/s throughput
over 1,024-token contexts and prefill latencies of 0.55--1.15 s for 64--128
token prompts, marking a significant energy-efficiency advance and establishing
a new edge FPGA benchmark for generative AI.
