---
layout: publication
title: 'RAP: Runtime-adaptive Pruning For LLM Inference'
authors: Huanrong Liu, Chunlin Tian, Xuyang Wei, Jiaheng Dai, Qin Liu, Tianqi Wei, Qingbiao Li, Li Li
conference: "Arxiv"
year: 2025
bibkey: liu2025runtime
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17138"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Pruning', 'Attention Mechanism']
---
Large language models (LLMs) excel at language understanding and generation, but their enormous computational and memory requirements hinder deployment. Compression offers a potential solution to mitigate these constraints. However, most existing methods rely on fixed heuristics and thus fail to adapt to runtime memory variations or heterogeneous KV-cache demands arising from diverse user requests. To address these limitations, we propose RAP, an elastic pruning framework driven by reinforcement learning (RL) that dynamically adjusts compression strategies in a runtime-aware manner. Specifically, RAP dynamically tracks the evolving ratio between model parameters and KV-cache across practical execution. Recognizing that FFNs house most parameters, whereas parameter -light attention layers dominate KV-cache formation, the RL agent retains only those components that maximize utility within the current memory budget, conditioned on instantaneous workload and device state. Extensive experiments results demonstrate that RAP outperforms state-of-the-art baselines, marking the first time to jointly consider model weights and KV-cache on the fly.
