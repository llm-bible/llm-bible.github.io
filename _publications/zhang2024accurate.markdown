---
layout: publication
title: 'Sageattention: Accurate 8-bit Attention For Plug-and-play Inference Acceleration'
authors: Jintao Zhang, Jia Wei, Haofeng Huang, Pengle Zhang, Jun Zhu, Jianfei Chen
conference: "The Thirteenth International Conference on Learning Representations (ICLR 2025)"
year: 2024
bibkey: zhang2024accurate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02367"}
  - {name: "Code", url: "https://github.com/thu-ml/SageAttention"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Quantization', 'Pretraining Methods', 'Transformer', 'Has Code', 'Attention Mechanism']
---
The transformer architecture predominates across various models. As the heart of the transformer, attention has a computational complexity of \\(O(N^2)\\), compared to \\(O(N)\\) for linear transformations. When handling large sequence lengths, attention becomes the primary time-consuming component. Although quantization has proven to be an effective method for accelerating model inference, existing quantization methods primarily focus on optimizing the linear layer. In response, we first analyze the feasibility of quantization in attention detailedly. Following that, we propose SageAttention, a highly efficient and accurate quantization method for attention. The OPS (operations per second) of our approach outperforms FlashAttention2 and xformers by about 2.1 times and 2.7 times, respectively. SageAttention also achieves superior accuracy performance over FlashAttention3. Comprehensive experiments confirm that our approach incurs almost no end-to-end metrics loss across diverse models, including those for large language processing, image generation, and video generation. The codes are available at https://github.com/thu-ml/SageAttention.
