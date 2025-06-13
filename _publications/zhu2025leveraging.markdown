---
layout: publication
title: 'Leveraging Compute-in-memory For Efficient Generative Model Inference In Tpus'
authors: Zhantong Zhu, Hongou Li, Wenjie Ren, Meng Wu, Le Ye, Ru Huang, Tianyu Jia
conference: "Arxiv"
year: 2025
bibkey: zhu2025leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.00461"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'RAG', 'Merging', 'Pretraining Methods', 'Transformer']
---
With the rapid advent of generative models, efficiently deploying these
models on specialized hardware has become critical. Tensor Processing Units
(TPUs) are designed to accelerate AI workloads, but their high power
consumption necessitates innovations for improving efficiency.
Compute-in-memory (CIM) has emerged as a promising paradigm with superior area
and energy efficiency. In this work, we present a TPU architecture that
integrates digital CIM to replace conventional digital systolic arrays in
matrix multiply units (MXUs). We first establish a CIM-based TPU architecture
model and simulator to evaluate the benefits of CIM for diverse generative
model inference. Building upon the observed design insights, we further explore
various CIM-based TPU architectural design choices. Up to 44.2% and 33.8%
performance improvement for large language model and diffusion transformer
inference, and 27.3x reduction in MXU energy consumption can be achieved with
different design choices, compared to the baseline TPUv4i architecture.
