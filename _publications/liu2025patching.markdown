---
layout: publication
title: 'PAVE: Patching And Adapting Video Large Language Models'
authors: Zhuoming Liu, Yiquan Li, Khoi Duc Nguyen, Yiwu Zhong, Yin Li
conference: "Arxiv"
year: 2025
bibkey: liu2025patching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.19794"}
  - {name: "Code", url: "https://github.com/dragonlzm/PAVE"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'Has Code', 'Applications']
---
Pre-trained video large language models (Video LLMs) exhibit remarkable
reasoning capabilities, yet adapting these models to new tasks involving
additional modalities or data types (e.g., audio or 3D information) remains
challenging. In this paper, we present PAVE, a flexible framework for adapting
pre-trained Video LLMs to downstream tasks with side-channel signals, such as
audio, 3D cues, or multi-view videos. PAVE introduces lightweight adapters,
referred to as "patches," which add a small number of parameters and operations
to a base model without modifying its architecture or pre-trained weights. In
doing so, PAVE can effectively adapt the pre-trained base model to support
diverse downstream tasks, including audio-visual question answering, 3D
reasoning, multi-view video recognition, and high frame rate video
understanding. Across these tasks, PAVE significantly enhances the performance
of the base model, surpassing state-of-the-art task-specific models while
incurring a minor cost of ~0.1% additional FLOPs and parameters. Further, PAVE
supports multi-task learning and generalizes well across different Video LLMs.
Our code is available at https://github.com/dragonlzm/PAVE.
