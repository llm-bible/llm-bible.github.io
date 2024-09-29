---
layout: publication
title: Flashattention-2&#58; Faster Attention With Better Parallelism And Work Partitioning
authors: Dao Tri
conference: "Arxiv"
year: 2023
bibkey: dao2023flashattention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2307.08691"}
tags: ['Applications', 'Attention Mechanism', 'Efficiency And Optimization', 'GPT', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Scaling Transformers to longer sequence lengths has been a major problem in the last several years promising to improve performance in language modeling and high-resolution image understanding as well as to unlock new applications in code audio and video generation. The attention layer is the main bottleneck in scaling to longer sequences as its runtime and memory increase quadratically in the sequence length. FlashAttention exploits the asymmetric GPU memory hierarchy to bring significant memory saving (linear instead of quadratic) and runtime speedup (2-4(times) compared to optimized baselines) with no approximation. However FlashAttention is still not nearly as fast as optimized matrix-multiply (GEMM) operations reaching only 25-4037; of the theoretical maximum FLOPs/s. We observe that the inefficiency is due to suboptimal work partitioning between different thread blocks and warps on the GPU causing either low-occupancy or unnecessary shared memory reads/writes. We propose FlashAttention-2 with better work partitioning to address these issues. In particular we (1) tweak the algorithm to reduce the number of non-matmul FLOPs (2) parallelize the attention computation even for a single head across different thread blocks to increase occupancy and (3) within each thread block distribute the work between warps to reduce communication through shared memory. These yield around 2(times) speedup compared to FlashAttention reaching 50-7337; of the theoretical maximum FLOPs/s on A100 and getting close to the efficiency of GEMM operations. We empirically validate that when used end-to-end to train GPT-style models FlashAttention-2 reaches training speed of up to 225 TFLOPs/s per A100 GPU (7237; model FLOPs utilization).
