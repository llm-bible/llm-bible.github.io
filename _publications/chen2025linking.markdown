---
layout: publication
title: 'PIS: Linking Importance Sampling And Attention Mechanisms For Efficient Prompt Compression'
authors: Lizhe Chen, Binjia Zhou, Yuyao Ge, Jiayi Chen, Shiguang Ni
conference: "Arxiv"
year: 2025
bibkey: chen2025linking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.16574"}
tags: ['Transformer', 'Tools', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Prompting']
---
Large language models (LLMs) have achieved remarkable progress, demonstrating
unprecedented capabilities across various natural language processing tasks.
However, the high costs associated with such exceptional performance limit the
widespread adoption of LLMs, highlighting the need for prompt compression.
Existing prompt compression methods primarily rely on heuristic truncation or
abstractive summarization techniques, which fundamentally overlook the
intrinsic mechanisms of LLMs and lack a systematic evaluation of token
importance for generation. In this work, we introduce Prompt Importance
Sampling (PIS), a novel compression framework that dynamically compresses
prompts by sampling important tokens based on the analysis of attention scores
of hidden states. PIS employs a dual-level compression mechanism: 1) at the
token level, we quantify saliency using LLM-native attention scores and
implement adaptive compression through a lightweight 9-layer reinforcement
learning (RL) network; 2) at the semantic level, we propose a Russian roulette
sampling strategy for sentence-level importance sampling. Comprehensive
evaluations across multiple domain benchmarks demonstrate that our method
achieves state-of-the-art compression performance. Notably, our framework
serendipitously enhances reasoning efficiency through optimized context
structuring. This work advances prompt engineering by offering both theoretical
grounding and practical efficiency in context management for LLMs.
