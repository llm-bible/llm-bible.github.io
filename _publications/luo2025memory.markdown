---
layout: publication
title: 'Headinfer: Memory-efficient LLM Inference By Head-wise Offloading'
authors: Cheng Luo, Zefan Cai, Hanshi Sun, Jinqi Xiao, Bo Yuan, Wen Xiao, Junjie Hu, Jiawei Zhao, Beidi Chen, Anima Anandkumar
conference: "Arxiv"
year: 2025
bibkey: luo2025memory
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12574"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Language Modeling', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
Transformer-based large language models (LLMs) demonstrate impressive
performance in long context generation. Extending the context length has
disproportionately shifted the memory footprint of LLMs during inference to the
key-value cache (KV cache). In this paper, we propose HEADINFER, which offloads
the KV cache to CPU RAM while avoiding the need to fully store the KV cache for
any transformer layer on the GPU. HEADINFER employs a fine-grained, head-wise
offloading strategy, maintaining only selective attention heads KV cache on the
GPU while computing attention output dynamically. Through roofline analysis, we
demonstrate that HEADINFER maintains computational efficiency while
significantly reducing memory footprint. We evaluate HEADINFER on the
Llama-3-8B model with a 1-million-token sequence, reducing the GPU memory
footprint of the KV cache from 128 GB to 1 GB and the total GPU memory usage
from 207 GB to 17 GB, achieving a 92% reduction compared to BF16 baseline
inference. Notably, HEADINFER enables 4-million-token inference with an 8B
model on a single consumer GPU with 24GB memory (e.g., NVIDIA RTX 4090) without
approximation methods.
