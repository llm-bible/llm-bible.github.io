---
layout: publication
title: 'Think Before You Accept: Semantic Reflective Verification For Faster Speculative Decoding'
authors: Yixuan Wang, Yijun Liu, Shiyu Ji, Yuzhuang Xu, Yang Xu, Qingfu Zhu, Wanxiang Che
conference: "Arxiv"
year: 2025
bibkey: wang2025think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18629"}
tags: ['Efficiency and Optimization', 'RAG', 'Merging', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Large language models (LLMs) suffer from high inference latency due to the auto-regressive decoding process. Speculative decoding accelerates inference by generating multiple draft tokens using a lightweight model and verifying them in parallel. However, existing verification methods rely heavily on distributional consistency while overlooking semantic correctness, thereby limiting the potential speedup of speculative decoding. While some methods employ additional models for relaxed verification of draft tokens, they often fail to generalize effectively to more diverse or open-domain settings. In this work, we propose Reflective Verification, a training-free and semantics-aware approach that achieves a better trade-off between correctness and efficiency. Specifically, we leverage the inherent reflective capacity of LLMs to semantically assess the correctness of draft tokens in parallel during verification. Using prompt-based probing, we obtain both the original and reflective distributions of draft tokens in a single forward pass. The fusion of these distributions enables semantic-level verification of draft tokens that incorporates both consistency and correctness. Experiments across multiple domain benchmarks and model scales demonstrate that our method significantly increases the acceptance length of draft tokens without compromising model performance. Furthermore, we find that the proposed Reflective Verification is orthogonal to existing statistical verification methods, and their combination yields additional 5\\(\sim\\)15% improvements in decoding speed.
