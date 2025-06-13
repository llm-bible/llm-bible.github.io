---
layout: publication
title: 'Gformer: Accelerating Large Language Models With Optimized Transformers On Gaudi Processors'
authors: Chengming Zhang, Xinheng Ding, Baixi Sun, Xiaodong Yu, Weijian Zheng, Zhen Xie, Dingwen Tao
conference: "Arxiv"
year: 2024
bibkey: zhang2024accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.19829"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Heterogeneous hardware like Gaudi processor has been developed to enhance
computations, especially matrix operations for Transformer-based large language
models (LLMs) for generative AI tasks. However, our analysis indicates that
Transformers are not fully optimized on such emerging hardware, primarily due
to inadequate optimizations in non-matrix computational kernels like Softmax
and in heterogeneous resource utilization, particularly when processing long
sequences. To address these issues, we propose an integrated approach (called
GFormer) that merges sparse and linear attention mechanisms. GFormer aims to
maximize the computational capabilities of the Gaudi processor's Matrix
Multiplication Engine (MME) and Tensor Processing Cores (TPC) without
compromising model quality. GFormer includes a windowed self-attention kernel
and an efficient outer product kernel for causal linear attention, aiming to
optimize LLM inference on Gaudi processors. Evaluation shows that GFormer
significantly improves efficiency and model performance across various tasks on
the Gaudi processor and outperforms state-of-the-art GPUs.
