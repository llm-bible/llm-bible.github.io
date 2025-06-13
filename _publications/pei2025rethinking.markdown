---
layout: publication
title: 'Rethinking Causal Mask Attention For Vision-language Inference'
authors: Xiaohuan Pei, Tao Huang, Yanxiang Ma, Chang Xu
conference: "Arxiv"
year: 2025
bibkey: pei2025rethinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.18605"}
tags: ['Tools', 'GPT', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Pretraining Methods', 'Multimodal Models']
---
Causal attention has become a foundational mechanism in autoregressive vision-language models (VLMs), unifying textual and visual inputs under a single generative framework. However, existing causal mask-based strategies are inherited from large language models (LLMs) where they are tailored for text-only decoding, and their adaptation to vision tokens is insufficiently addressed in the prefill stage. Strictly masking future positions for vision queries introduces overly rigid constraints, which hinder the model's ability to leverage future context that often contains essential semantic cues for accurate inference. In this work, we empirically investigate how different causal masking strategies affect vision-language inference and then propose a family of future-aware attentions tailored for this setting. We first empirically analyze the effect of previewing future tokens for vision queries and demonstrate that rigid masking undermines the model's capacity to capture useful contextual semantic representations. Based on these findings, we propose a lightweight attention family that aggregates future visual context into past representations via pooling, effectively preserving the autoregressive structure while enhancing cross-token dependencies. We evaluate a range of causal masks across diverse vision-language inference settings and show that selectively compressing future semantic context into past representations benefits the inference.
