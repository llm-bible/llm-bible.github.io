---
layout: publication
title: 'Heterollm: Accelerating Large Language Model Inference On Mobile Socs Platform With Heterogeneous AI Accelerators'
authors: Le Chen, Dahu Feng, Erhu Feng, Rong Zhao, Yingrui Wang, Yubin Xia, Haibo Chen, Pinjie Xu
conference: "Arxiv"
year: 2025
bibkey: chen2025accelerating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.14794"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT']
---
With the rapid advancement of artificial intelligence technologies such as
ChatGPT, AI agents and video generation,contemporary mobile systems have begun
integrating these AI capabilities on local devices to enhance privacy and
reduce response latency. To meet the computational demands of AI tasks, current
mobile SoCs are equipped with diverse AI accelerators, including GPUs and
Neural Processing Units (NPUs). However, there has not been a comprehensive
characterization of these heterogeneous processors, and existing designs
typically only leverage a single AI accelerator for LLM inference, leading to
suboptimal use of computational resources and memory bandwidth. In this paper,
we first summarize key performance characteristics of mobile SoC, including
heterogeneous processors, unified memory, synchronization, etc. Drawing on
these observations, we propose different tensor partition strategies to fulfill
the distinct requirements of the prefill and decoding phases. We further design
a fast synchronization mechanism that leverages the unified memory address
provided by mobile SoCs. By employing these techniques, we present HeteroLLM,
the fastest LLM inference engine in mobile devices which supports both
layer-level and tensor-level heterogeneous execution. Evaluation results show
that HeteroLLM achieves 9.99 and 4.36 performance improvement over other
mobile-side LLM inference engines: MLC and MNN.
