---
layout: publication
title: 'Bridging The Dimensional Chasm: Uncover Layer-wise Dimensional Reduction In Transformers Through Token Correlation'
authors: Zhuo-yang Song, Zeyu Li, Qing-hong Cao, Ming-xing Luo, Hua Xing Zhu
conference: "Arxiv"
year: 2025
bibkey: song2025bridging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.22547"}
tags: ['Model Architecture', 'Tools', 'Pretraining Methods', 'Transformer', 'Interpretability and Explainability']
---
The geometric evolution of token representations in large language models
(LLMs) presents a fundamental paradox: while human language inherently
organizes semantic information in low-dimensional spaces (\\(\sim 10^1\\)
dimensions), modern LLMs employ high-dimensional embeddings (\\(\sim 10^3\\)
dimensions) processed through Transformer architectures. To resolve this
paradox, this work bridges this conceptual gap by developing a geometric
framework that tracks token dynamics across Transformers layers. Through
layer-wise analysis of intrinsic dimensions across multiple architectures, we
reveal an expansion-contraction pattern where tokens diffuse to a "working
space" and then progressively project onto lower-dimensional submanifolds. Our
finding implies a negative correlation between the working space dimension and
parameter-sensitive performance of the LLMs, and indicates that effective
models tend to compress tokens into approximately 10-dimensional submanifolds,
closely resembling human semantic spaces. This work not only advances LLM
interpretability by reframing Transformers layers as projectors that mediate
between high-dimensional computation and low-dimensional semantics, but also
provides practical tools for model diagnostics that do not rely on
task-specific evaluations.
