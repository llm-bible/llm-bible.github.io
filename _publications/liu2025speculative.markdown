---
layout: publication
title: 'Speculative Prefill: Turbocharging TTFT With Lightweight And Training-free Token Importance Estimation'
authors: Jingyu Liu, Beidi Chen, Ce Zhang
conference: "Arxiv"
year: 2025
bibkey: liu2025speculative
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.02789"}
tags: ['Transformer', 'Tools', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Prompting']
---
Improving time-to-first-token (TTFT) is an essentially important objective in modern large language model (LLM) inference engines. Optimizing TTFT directly results in higher maximal QPS and meets the requirements of many critical applications. However, boosting TTFT is notoriously challenging since it is compute-bounded and the performance bottleneck shifts from the self-attention that many prior works focus on to the MLP part. In this work, we present SpecPrefill, a training free framework that accelerates the inference TTFT for both long and medium context queries based on the following insight: LLMs are generalized enough to preserve the quality given only a carefully chosen subset of prompt tokens. At its core, SpecPrefill leverages a lightweight model to speculate locally important tokens based on the context. These tokens, along with the necessary positional information, are then sent to the main model for processing. We evaluate SpecPrefill with a diverse set of tasks, followed by a comprehensive benchmarking of performance improvement both in a real end-to-end setting and ablation studies. SpecPrefill manages to serve Llama-3.1-405B-Instruct-FP8 with up to 7\\(\times\\) maximal end-to-end QPS on real downstream tasks and 7.66\\(\times\\) TTFT improvement.
