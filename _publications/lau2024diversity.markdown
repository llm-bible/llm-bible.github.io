---
layout: publication
title: 'Dipper: Diversity In Prompts For Producing Large Language Model Ensembles In Reasoning Tasks'
authors: Gregory Kang Ruey Lau, Wenyang Hu, Diwen Liu, Jizhuo Chen, See-kiong Ng, Bryan Kian Hsiang Low
conference: "Arxiv"
year: 2024
bibkey: lau2024diversity
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.15238'}
tags: ['Training Techniques', 'Prompting', 'Tools', 'Merging']
---
Large Language Models still encounter substantial challenges in reasoning
tasks, especially for smaller models, which many users may be restricted to due
to resource constraints (e.g. GPU memory restrictions). Inference-time methods
to boost LLM performance, such as prompting methods to invoke certain reasoning
pathways in responses, have been shown effective in past works, though they
largely rely on sequential queries. The ensemble method, which consists of
multiple constituent models running in parallel, is a promising approach to
achieving better inference-time performance, especially given recent
developments that enabled significant speed-ups in LLM batch inference. In this
work, we propose a novel, training-free LLM ensemble framework where a single
LLM model is fed an optimized, diverse set of prompts in parallel, effectively
producing an ensemble at inference time to achieve performance improvement in
reasoning tasks. We empirically demonstrate that our method leads to
significant gains on math reasoning tasks, e.g., on MATH, where our ensemble
consisting of a few small models (e.g., three Qwen2-MATH-1.5B-it models) can
outperform a larger model (e.g., Qwen2-MATH-7B-it).
