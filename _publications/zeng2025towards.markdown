---
layout: publication
title: 'Towards Context-robust Llms: A Gated Representation Fine-tuning Approach'
authors: Shenglai Zeng, Pengfei He, Kai Guo, Tianqi Zheng, Hanqing Lu, Yue Xing, Hui Liu
conference: "Arxiv"
year: 2025
bibkey: zeng2025towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.14100'}
tags: ['RAG', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) enhanced with external contexts, such as through
retrieval-augmented generation (RAG), often face challenges in handling
imperfect evidence. They tend to over-rely on external knowledge, making them
vulnerable to misleading and unhelpful contexts. To address this, we propose
the concept of context-robust LLMs, which can effectively balance internal
knowledge with external context, similar to human cognitive processes.
Specifically, context-robust LLMs should rely on external context only when
lacking internal knowledge, identify contradictions between internal and
external knowledge, and disregard unhelpful contexts. To achieve this goal, we
introduce Grft, a lightweight and plug-and-play gated representation
fine-tuning approach. Grft consists of two key components: a gating mechanism
to detect and filter problematic inputs, and low-rank representation adapters
to adjust hidden representations. By training a lightweight intervention
function with only 0.0004% of model size on fewer than 200 examples, Grft can
effectively adapt LLMs towards context-robust behaviors.
