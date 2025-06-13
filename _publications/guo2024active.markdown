---
layout: publication
title: 'Active-dormant Attention Heads: Mechanistically Demystifying Extreme-token Phenomena In Llms'
authors: Tianyu Guo, Druv Pai, Yu Bai, Jiantao Jiao, Michael I. Jordan, Song Mei
conference: "Arxiv"
year: 2024
bibkey: guo2024active
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.13835"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Model Architecture', 'Quantization', 'Pretraining Methods', 'Transformer', 'Interpretability and Explainability', 'Attention Mechanism']
---
Practitioners have consistently observed three puzzling phenomena in
transformer-based large language models (LLMs): attention sinks, value-state
drains, and residual-state peaks, collectively referred to as extreme-token
phenomena. These phenomena are characterized by certain so-called "sink tokens"
receiving disproportionately high attention weights, exhibiting significantly
smaller value states, and having much larger residual-state norms than those of
other tokens. These extreme tokens give rise to various challenges in LLM
inference, quantization, and interpretability.
  We elucidate the mechanisms behind extreme-token phenomena. First, we show
that these phenomena arise in very simple architectures -- transformers with
one to three layers -- trained on a toy model, the Bigram-Backcopy (BB) task.
In this setting, we identify an active-dormant mechanism, where attention heads
become sinks for specific input domains while remaining non-sinks for others.
Our theoretical analysis of the training dynamics reveals that these phenomena
are driven by a mutual reinforcement mechanism. Building on these insights, we
propose strategies to mitigate extreme-token phenomena during pretraining,
including replacing softmax with ReLU and Adam with SGD. Next, we extend our
analysis to pretrained LLMs, including Llama and OLMo, showing that many
attention heads exhibit a similar active-dormant mechanism as in the BB task,
and that the mutual reinforcement mechanism also governs the emergence of
extreme-token phenomena during LLM pretraining. Our results reveal that many of
the static and dynamic properties of extreme-token phenomena predicted by the
BB task align with observations in pretrained LLMs.
