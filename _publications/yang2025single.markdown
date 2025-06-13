---
layout: publication
title: 'Haplovl: A Single-transformer Baseline For Multi-modal Understanding'
authors: Rui Yang, Lin Song, Yicheng Xiao, Runhui Huang, Yixiao Ge, Ying Shan, Hengshuang Zhao
conference: "Arxiv"
year: 2025
bibkey: yang2025single
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.14694'}
tags: ['Transformer', 'Training Techniques', 'Model Architecture', 'Merging', 'Reinforcement Learning', 'Pretraining Methods']
---
Recent advancements in large language models (LLMs) have significantly
propelled the development of large multi-modal models (LMMs), highlighting the
potential for general and intelligent assistants. However, most LMMs model
visual and textual modalities separately, leading to recent efforts to develop
native LMMs using a single transformer. Despite the promise, these native
models are resource-intensive and often exhibit performance gaps compared to
their compositional counterparts. To alleviate this issue, we propose a simple
yet efficient method to construct a baseline for the native and end-to-end
large multi-modal model in a single transformer. First, we propose a new
early-fusion LMM that can fuse multi-modal inputs in the early stage and
respond to visual instructions in an auto-regressive manner. Second, we devise
an efficient training recipe for the proposed model, which harnesses the prior
knowledge of the pre-trained models, addressing both the performance
limitations and the challenge of resource consumption. The proposed model
demonstrates superior performance compared to other LMMs using one transformer
and significantly narrows the performance gap with compositional LMMs.
