---
layout: publication
title: Instinfer: In-storage Attention Offloading For Cost-effective Long-context LLM Inference
authors: Pan Xiurui, Li Endian, Li Qiao, Liang Shengwen, Shan Yizhou, Zhou Ke, Luo Yingwei, Wang Xiaolin, Zhang Jie
conference: "Arxiv"
year: 2024
bibkey: pan2024attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.04992"}
tags: ['Attention Mechanism', 'Model Architecture', 'Pretraining Methods', 'RAG']
---
The widespread of Large Language Models (LLMs) marks a significant milestone in generative AI. Nevertheless the increasing context length and batch size in offline LLM inference escalate the memory requirement of the key-value (KV) cache which imposes a huge burden on the GPU VRAM especially for resource-constraint scenarios (e.g. edge computing and personal devices). Several cost-effective solutions leverage host memory or SSDs to reduce storage costs for offline inference scenarios and improve the throughput. Nevertheless they suffer from significant performance penalties imposed by intensive KV cache accesses due to limited PCIe bandwidth. To address these issues we propose InstInfer a novel LLM inference system that offloads the most performance-critical computation (i.e. attention in decoding phase) and data (i.e. KV cache) parts to Computational Storage Drives (CSDs) which minimize the enormous KV transfer overheads. InstInfer designs a dedicated flash-aware in-storage attention engine with KV cache management mechanisms to exploit the high internal bandwidths of CSDs instead of being limited by the PCIe bandwidth. The optimized P2P transmission between GPU and CSDs further reduces data migration overheads. Experimental results demonstrate that for a 13B model using an NVIDIA A6000 GPU InstInfer improves throughput for long-sequence inference by up to 11.1(times) compared to existing SSD-based solutions such as FlexGen.
