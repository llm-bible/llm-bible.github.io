---
layout: publication
title: 'Deco: Decoupling Token Compression From Semantic Abstraction In Multimodal Large Language Models'
authors: Yao Linli, Li Lei, Ren Shuhuai, Wang Lean, Liu Yuanxin, Sun Xu, Hou Lu
conference: "Arxiv"
year: 2024
bibkey: yao2024decoupling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.20985"}
tags: ['Efficiency And Optimization', 'Multimodal Models', 'Training Techniques']
---
The visual projector, which bridges the vision and language modalities and
facilitates cross-modal alignment, serves as a crucial component in MLLMs.
However, measuring the effectiveness of projectors in vision-language alignment
remains under-explored, which currently can only be inferred from the
performance of MLLMs on downstream tasks. Motivated by the problem, this study
examines the projector module by interpreting the vision-language semantic flow
within MLLMs. Specifically, we trace back the semantic relevance flow from
generated language tokens to raw visual encoder patches and the intermediate
outputs produced by projectors. Our findings reveal that compressive projectors
(e.g., QFormer), abstract visual patches into a limited set of semantic
concepts, such as objects or attributes, resulting in a 'double abstraction'
phenomenon. This involves a first visual semantic abstraction by the projector
referring to pre-defined query tokens, and a second extraction by the LLM based
on text instructions. The double abstraction is inefficient in training and
will result in cumulative vision semantics deficiency. To mitigate this issue,
we propose the key insight of 'Decouple Compression from Abstraction (DeCo),
that is compressing the visual token number at the patch level by projectors
and allowing the LLM to handle visual semantic abstraction entirely.
Consequently, we adopt a simple compressor, i.e., 2D Adaptive Pooling, to
downsample visual patches in a parameter-free manner. Empirical evaluation
demonstrates that DeCo surpasses traditional compressive projectors regarding
both performance and efficiency. It achieves performance gains of 0.9%, 7.1%,
and 2.9% across the MLLM Benchmarks, Visual Localization, and Open-ended VQA
tasks with fewer trainable parameters and faster convergence speed.
