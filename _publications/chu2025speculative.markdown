---
layout: publication
title: 'SSR: Speculative Parallel Scaling Reasoning In Test-time'
authors: Yuanlin Chu, Bo Wang, Xiang Liu, Hong Chen, Aiwei Liu, Xuming Hu
conference: "Arxiv"
year: 2025
bibkey: chu2025speculative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15340"}
tags: ['Tools', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have achieved impressive results on multi-step mathematical reasoning, yet at the cost of high computational overhead. This challenge is particularly acute for test-time scaling methods such as parallel decoding, which increase answer diversity but scale poorly in efficiency. To address this efficiency-accuracy trade-off, we propose SSR (Speculative Parallel Scaling Reasoning), a training-free framework that leverages a key insight: by introducing speculative decoding at the step level, we can accelerate reasoning without sacrificing correctness. SSR integrates two components: a Selective Parallel Module (SPM) that identifies a small set of promising reasoning strategies via model-internal scoring, and Step-level Speculative Decoding (SSD), which enables efficient draft-target collaboration for fine-grained reasoning acceleration. Experiments on three mathematical benchmarks-AIME 2024, MATH-500, and LiveMathBench - demonstrate that SSR achieves strong gains over baselines. For instance, on LiveMathBench, SSR improves pass@1 accuracy by 13.84% while reducing computation to 80.5% of the baseline FLOPs. On MATH-500, SSR reduces compute to only 30% with no loss in accuracy.
