---
layout: publication
title: 'Spargeattention: Accurate And Training-free Sparse Attention Accelerating Any Model Inference'
authors: Jintao Zhang, Chendong Xiang, Haofeng Huang, Jia Wei, Haocheng Xi, Jun Zhu, Jianfei Chen
conference: "Proceedings of the 42 nd International Conference on Machine Learning PMLR 267 2025 (ICML 2025)"
year: 2025
bibkey: zhang2025accurate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.18137"}
  - {name: "Code", url: "https://github.com/thu-ml/SpargeAttn"}
tags: ['Tools', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code']
---
An efficient attention implementation is essential for large models due to its quadratic time complexity. Fortunately, attention commonly exhibits sparsity, i.e., many values in the attention map are near zero, allowing for the omission of corresponding computations. Many studies have utilized the sparse pattern to accelerate attention. However, most existing works focus on optimizing attention within specific models by exploiting certain sparse patterns of the attention map. A universal sparse attention that guarantees both the speedup and end-to-end performance of diverse models remains elusive. In this paper, we propose SpargeAttn, a universal sparse and quantized attention for any model. Our method uses a two-stage online filter: in the first stage, we rapidly and accurately predict the attention map, enabling the skip of some matrix multiplications in attention. In the second stage, we design an online softmax-aware filter that incurs no extra overhead and further skips some matrix multiplications. Experiments show that our method significantly accelerates diverse models, including language, image, and video generation, without sacrificing end-to-end metrics. The codes are available at https://github.com/thu-ml/SpargeAttn.
