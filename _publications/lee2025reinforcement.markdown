---
layout: publication
title: 'Refocus: Reinforcement-guided Frame Optimization For Contextual Understanding'
authors: Hosu Lee, Junho Kim, Hyunjun Kim, Yong Man Ro
conference: "Arxiv"
year: 2025
bibkey: lee2025reinforcement
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01274"}
tags: ['Agentic', 'GPT', 'Efficiency and Optimization', 'Tools', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods', 'Multimodal Models']
---
Recent progress in Large Multi-modal Models (LMMs) has enabled effective vision-language reasoning, yet the ability to understand video content remains constrained by suboptimal frame selection strategies. Existing approaches often rely on static heuristics or external retrieval modules to feed frame information into video-LLMs, which may fail to provide the query-relevant information. In this work, we introduce ReFoCUS (Reinforcement-guided Frame Optimization for Contextual UnderStanding), a novel frame-level policy optimization framework that shifts the optimization target from textual responses to visual input selection. ReFoCUS learns a frame selection policy via reinforcement learning, using reward signals derived from a reference LMM to reflect the model's intrinsic preferences for frames that best support temporally grounded responses. To efficiently explore the large combinatorial frame space, we employ an autoregressive, conditional selection architecture that ensures temporal coherence while reducing complexity. Our approach does not require explicit supervision at the frame-level and consistently improves reasoning performance across multiple video QA benchmarks, highlighting the benefits of aligning frame selection with model-internal utility.
