---
layout: publication
title: 'Practical Offloading For Fine-tuning LLM On Commodity GPU Via Learned Sparse Projectors'
authors: Siyuan Chen, Zhuofeng Wang, Zelong Guan, Yudong Liu, Phillip B. Gibbons
conference: "Arxiv"
year: 2024
bibkey: chen2024practical
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.10181"}
  - {name: "Code", url: "https://github.com/gulang2019/LSP-Offload"}
tags: ['Fine-Tuning', 'Tools', 'Training Techniques', 'Has Code', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) requires significant memory, often
exceeding the capacity of a single GPU. A common solution to this memory
challenge is offloading compute and data from the GPU to the CPU. However, this
approach is hampered by the limited bandwidth of commodity hardware, which
constrains communication between the CPU and GPU, and by slower matrix
multiplications on the CPU.
  In this paper, we present an offloading framework, LSP-Offload, that enables
near-native speed LLM fine-tuning on commodity hardware through learned sparse
projectors. Our data-driven approach involves learning efficient sparse
compressors that minimize communication with minimal precision loss.
Additionally, we introduce a novel layer-wise communication schedule to
maximize parallelism between communication and computation. As a result, our
framework can fine-tune a 1.3 billion parameter model on a 4GB laptop GPU and a
6.7 billion parameter model on a 24GB NVIDIA RTX 4090 GPU. Compared to
state-of-the-art offloading frameworks, our approach reduces end-to-end
fine-tuning time by 33.1%-62.5% when converging to the same accuracy. We open
source our framework at https://github.com/gulang2019/LSP-Offload.
