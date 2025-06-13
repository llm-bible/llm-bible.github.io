---
layout: publication
title: 'Langbridge: Interpreting Image As A Combination Of Language Embeddings'
authors: Jiaqi Liao, Yuwei Niu, Fanqing Meng, Hao Li, Changyao Tian, Yinuo Du, Yuwen Xiong, Dianqi Li, Xizhou Zhu, Li Yuan, Jifeng Dai, Yu Cheng
conference: "Arxiv"
year: 2025
bibkey: liao2025interpreting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.19404"}
tags: ['Training Techniques', 'Multimodal Models', 'Pretraining Methods', 'Reinforcement Learning']
---
Recent years have witnessed remarkable advances in Large Vision-Language
Models (LVLMs), which have achieved human-level performance across various
complex vision-language tasks. Following LLaVA's paradigm, mainstream LVLMs
typically employ a shallow MLP for visual-language alignment through a
two-stage training process: pretraining for cross-modal alignment followed by
instruction tuning. While this approach has proven effective, the underlying
mechanisms of how MLPs bridge the modality gap remain poorly understood.
Although some research has explored how LLMs process transformed visual tokens,
few studies have investigated the fundamental alignment mechanism. Furthermore,
the MLP adapter requires retraining whenever switching LLM backbones. To
address these limitations, we first investigate the working principles of MLP
adapters and discover that they learn to project visual embeddings into
subspaces spanned by corresponding text embeddings progressively. Based on this
insight, we propose LangBridge, a novel adapter that explicitly maps visual
tokens to linear combinations of LLM vocabulary embeddings. This innovative
design enables pretraining-free adapter transfer across different LLMs while
maintaining performance. Our experimental results demonstrate that a LangBridge
adapter pre-trained on Qwen2-0.5B can be directly applied to larger models such
as LLaMA3-8B or Qwen2.5-14B while maintaining competitive performance. Overall,
LangBridge enables interpretable vision-language alignment by grounding visual
representations in LLM vocab embedding, while its plug-and-play design ensures
efficient reuse across multiple LLMs with nearly no performance degradation.
See our project page at https://jiaqiliao77.github.io/LangBridge.github.io/
