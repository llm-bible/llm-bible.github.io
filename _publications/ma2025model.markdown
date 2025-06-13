---
layout: publication
title: 'Model Hemorrhage And The Robustness Limits Of Large Language Models'
authors: Ziyang Ma, Zuchao Li, Lefei Zhang, Gui-song Xia, Bo Du, Liangpei Zhang, Dacheng Tao
conference: "Arxiv"
year: 2025
bibkey: ma2025model
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.23924"}
tags: ['Security', 'Model Architecture', 'Efficiency and Optimization', 'Tools', 'Reinforcement Learning', 'Pruning', 'Quantization', 'Pretraining Methods', 'Transformer', 'Attention Mechanism']
---
Large language models (LLMs) demonstrate strong performance across natural
language processing tasks, yet undergo significant performance degradation when
modified for deployment through quantization, pruning, or decoding strategy
adjustments. We define this phenomenon as model hemorrhage - performance
decline caused by parameter alterations and architectural changes. Through
systematic analysis of various LLM frameworks, we identify key vulnerability
patterns: layer expansion frequently disrupts attention mechanisms, compression
techniques induce information loss cascades, and decoding adjustments amplify
prediction divergences. Our investigation reveals transformer architectures
exhibit inherent robustness thresholds that determine hemorrhage severity
across modification types. We propose three mitigation strategies:
gradient-aware pruning preserves critical weight pathways, dynamic quantization
scaling maintains activation integrity, and decoding calibration aligns
generation trajectories with original model distributions. This work
establishes foundational metrics for evaluating model stability during
adaptation, providing practical guidelines for maintaining performance while
enabling efficient LLM deployment. Our findings advance understanding of neural
network resilience under architectural transformations, particularly for
large-scale language models.
