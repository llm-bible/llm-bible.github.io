---
layout: publication
title: 'Toklip: Marry Visual Tokens To CLIP For Multimodal Comprehension And Generation'
authors: Haokun Lin, Teng Wang, Yixiao Ge, Yuying Ge, Zhichao Lu, Ying Wei, Qingfu Zhang, Zhenan Sun, Ying Shan
conference: "Arxiv"
year: 2025
bibkey: lin2025marry
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.05422"}
  - {name: "Code", url: "https://github.com/TencentARC/TokLIP"}
tags: ['Transformer', 'Efficiency and Optimization', 'GPT', 'Model Architecture', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models', 'Quantization']
---
Pioneering token-based works such as Chameleon and Emu3 have established a
foundation for multimodal unification but face challenges of high training
computational overhead and limited comprehension performance due to a lack of
high-level semantics. In this paper, we introduce TokLIP, a visual tokenizer
that enhances comprehension by semanticizing vector-quantized (VQ) tokens and
incorporating CLIP-level semantics while enabling end-to-end multimodal
autoregressive training with standard VQ tokens. TokLIP integrates a low-level
discrete VQ tokenizer with a ViT-based token encoder to capture high-level
continuous semantics. Unlike previous approaches (e.g., VILA-U) that discretize
high-level features, TokLIP disentangles training objectives for comprehension
and generation, allowing the direct application of advanced VQ tokenizers
without the need for tailored quantization operations. Our empirical results
demonstrate that TokLIP achieves exceptional data efficiency, empowering visual
tokens with high-level semantic understanding while enhancing low-level
generative capacity, making it well-suited for autoregressive Transformers in
both comprehension and generation tasks. The code and models are available at
https://github.com/TencentARC/TokLIP.
