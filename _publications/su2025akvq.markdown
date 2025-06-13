---
layout: publication
title: 'AKVQ-VL: Attention-aware KV Cache Adaptive 2-bit Quantization For Vision-language Models'
authors: Zunhai Su, Wang Shen, Linge Li, Zhe Chen, Hanyu Wei, Huangqi Yu, Kehong Yuan
conference: "Arxiv"
year: 2025
bibkey: su2025akvq
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.15021"}
tags: ['Multimodal Models', 'Model Architecture', 'Efficiency and Optimization', 'Reinforcement Learning', 'RAG', 'Quantization', 'Attention Mechanism']
---
Vision-language models (VLMs) show remarkable performance in multimodal
tasks. However, excessively long multimodal inputs lead to oversized Key-Value
(KV) caches, resulting in significant memory consumption and I/O bottlenecks.
Previous KV quantization methods for Large Language Models (LLMs) may alleviate
these issues but overlook the attention saliency differences of multimodal
tokens, resulting in suboptimal performance. In this paper, we investigate the
attention-aware token saliency patterns in VLM and propose AKVQ-VL. AKVQ-VL
leverages the proposed Text-Salient Attention (TSA) and Pivot-Token-Salient
Attention (PSA) patterns to adaptively allocate bit budgets. Moreover,
achieving extremely low-bit quantization requires effectively addressing
outliers in KV tensors. AKVQ-VL utilizes the Walsh-Hadamard transform (WHT) to
construct outlier-free KV caches, thereby reducing quantization difficulty.
Evaluations of 2-bit quantization on 12 long-context and multimodal tasks
demonstrate that AKVQ-VL maintains or even improves accuracy, outperforming
LLM-oriented methods. AKVQ-VL can reduce peak memory usage by 2.13x, support up
to 3.25x larger batch sizes and 2.46x throughput.
