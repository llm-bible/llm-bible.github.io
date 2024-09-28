---
layout: publication
title: Mixed Sparsity Training Achieving 4times FLOP Reduction for Transformer Pretraining
authors: Hu Pihe, Li Shaolong, Huang Longbo
conference: "Arxiv"
year: 2024
bibkey: hu2024mixed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.11746"}
tags: ['ARXIV', 'Attention Mechanism', 'GPT', 'LLM', 'Model Architecture', 'Transformer']
---
Large language models (LLMs) have made significant strides in complex tasks yet their widespread adoption is impeded by substantial computational demands. With hundreds of billion parameters transformer-based LLMs necessitate months of pretraining across a high-end GPU cluster. However this paper reveals a compelling finding transformers exhibit considerable redundancy in pretraining computations which motivates our proposed solution Mixed Sparsity Training (MST) an efficient pretraining method that can reduce about 75 of Floating Point Operations (FLOPs) while maintaining performance. MST integrates dynamic sparse training (DST) with Sparsity Variation (SV) and Hybrid Sparse Attention (HSA) during pretraining involving three distinct phases warm-up ultra-sparsification and restoration. The warm-up phase transforms the dense model into a sparse one and the restoration phase reinstates connections. Throughout these phases the model is trained with a dynamically evolving sparse topology and an HSA mechanism to maintain performance and minimize training FLOPs concurrently. Our experiment on GPT-2 showcases a FLOP reduction of 4times without compromising performance.
