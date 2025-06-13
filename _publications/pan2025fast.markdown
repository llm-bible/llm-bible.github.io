---
layout: publication
title: 'Specreason: Fast And Accurate Inference-time Compute Via Speculative Reasoning'
authors: Rui Pan, Yinwei Dai, Zhihao Zhang, Gabriele Oliaro, Zhihao Jia, Ravi Netravali
conference: "Arxiv"
year: 2025
bibkey: pan2025fast
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.07891"}
  - {name: "Code", url: "https://github.com/ruipeterpan/specreason"}
tags: ['GPT', 'Has Code', 'Pretraining Methods']
---
Recent advances in inference-time compute have significantly improved performance on complex tasks by generating long chains of thought (CoTs) using Large Reasoning Models (LRMs). However, this improved accuracy comes at the cost of high inference latency due to the length of generated reasoning sequences and the autoregressive nature of decoding. Our key insight in tackling these overheads is that LRM inference, and the reasoning that it embeds, is highly tolerant of approximations: complex tasks are typically broken down into simpler steps, each of which brings utility based on the semantic insight it provides for downstream steps rather than the exact tokens it generates. Accordingly, we introduce SpecReason, a system that automatically accelerates LRM inference by using a lightweight model to (speculatively) carry out simpler intermediate reasoning steps and reserving the costly base model only to assess (and potentially correct) the speculated outputs. Importantly, SpecReason's focus on exploiting the semantic flexibility of thinking tokens in preserving final-answer accuracy is complementary to prior speculation techniques, most notably speculative decoding, which demands token-level equivalence at each step. Across a variety of reasoning benchmarks, SpecReason achieves \\(1.4-3.0\times\\) speedup over vanilla LRM inference while improving accuracy by \\(0.4-9.0%\\). Compared to speculative decoding without SpecReason, their combination yields an additional \\(8.8-58.0%\\) latency reduction. We open-source SpecReason at https://github.com/ruipeterpan/specreason.
