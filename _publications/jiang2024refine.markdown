---
layout: publication
title: 'Refine Large Language Model Fine-tuning Via Instruction Vector'
authors: Gangwei Jiang, Zhaoyi Li, Defu Lian, Ying Wei
conference: "Arxiv"
year: 2024
bibkey: jiang2024refine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12227"}
tags: ['Fine-Tuning', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Fine-tuning large language models (LLMs) can cause them to lose their general
capabilities. However, the intrinsic mechanisms behind such forgetting remain
unexplored. In this paper, we begin by examining this phenomenon by focusing on
knowledge understanding and instruction following, with the latter identified
as the main contributor to forgetting during fine-tuning. Consequently, we
propose the Instruction Vector (IV) framework to capture model representations
highly related to specific instruction-following capabilities, thereby making
it possible to understand model-intrinsic forgetting. Through the analysis of
IV dynamics pre and post-training, we suggest that fine-tuning mostly adds
specialized reasoning patterns instead of erasing previous skills, which may
appear as forgetting. Building on this insight, we develop IV-guided training,
which aims to preserve original computation graph, thereby mitigating
catastrophic forgetting. Empirical tests on three benchmarks confirm the
efficacy of this new approach, supporting the relationship between IVs and
forgetting. Our code will be made available soon.
