---
layout: publication
title: 'Infifusion: A Unified Framework For Enhanced Cross-model Reasoning Via LLM Fusion'
authors: Zhaoyi Yan, Yiming Zhang, Baoyi He, Yuhao Fu, Qi Zhou, Zhijie Sang, Chunlin Ji, Shengyu Zhang, Fei Wu, Hongxia Yang
conference: "Arxiv"
year: 2025
bibkey: yan2025unified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.02795"}
tags: ['Tools', 'Efficiency and Optimization', 'Merging', 'Training Techniques', 'Distillation']
---
We introduce InfiFusion, an efficient training pipeline designed to integrate
multiple domain-specialized Large Language Models (LLMs) into a single pivot
model, effectively harnessing the strengths of each source model. Traditional
fusion methods either merge model parameters directly or rely on knowledge
distillation with rigid assumptions, limiting their flexibility and efficiency.
InfiFusion overcomes these limitations by enhancing Universal Logit
Distillation (ULD) with Top-K selection and Logits Standardization. We propose
two fusion strategies: Pairwise Fusion (InfiFusion\\(_p\\)), where each source
model knowledge is distilled individually into the pivot model followed by
merging and Unified Fusion (InfiFusion\\(_u\\)), where knowledge from all source
models is distilled simultaneously into the pivot model. InfiFusion outperforms
the state-of-the-art models, such as Qwen-2.5-14B-Instruct and Phi-4, across 11
widely applied benchmarks covering reasoning, coding, mathematics, and
instruction-following tasks. Notably, InfiFusion achieves this superior
performance while significantly reduces computational costs, completing full
training with only 160 H800 GPU hours compared to the millions typically
required for traditional LLM training.
