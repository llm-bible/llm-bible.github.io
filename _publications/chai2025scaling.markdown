---
layout: publication
title: 'LONGER: Scaling Up Long Sequence Modeling In Industrial Recommenders'
authors: Zheng Chai, Qin Ren, Xijun Xiao, Huizhi Yang, Bo Han, Sijun Zhang, Di Chen, Hui Lu, Wenlin Zhao, Lele Yu, Xionghang Xie, Shiru Ren, Xiang Sun, Yaocheng Tan, Peng Xu, Yuchao Zheng, Di Wu
conference: "Arxiv"
year: 2025
bibkey: chai2025scaling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04421"}
tags: ['Transformer', 'Pre-Training', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Large-Scale Training', 'RecSys', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Scaling Laws']
---
Modeling ultra-long user behavior sequences is critical for capturing both
long- and short-term preferences in industrial recommender systems. Existing
solutions typically rely on two-stage retrieval or indirect modeling paradigms,
incuring upstream-downstream inconsistency and computational inefficiency. In
this paper, we present LONGER, a Long-sequence Optimized traNsformer for
GPU-Efficient Recommenders. LONGER incorporates (i) a global token mechanism
for stabilizing attention over long contexts, (ii) a token merge module with
lightweight InnerTransformers and hybrid attention strategy to reduce quadratic
complexity, and (iii) a series of engineering optimizations, including training
with mixed-precision and activation recomputation, KV cache serving, and the
fully synchronous model training and serving framework for unified GPU-based
dense and sparse parameter updates. LONGER consistently outperforms strong
baselines in both offline metrics and online A/B testing in both advertising
and e-commerce services at ByteDance, validating its consistent effectiveness
and industrial-level scaling laws. Currently, LONGER has been fully deployed at
more than 10 influential scenarios at ByteDance, serving billion users.
