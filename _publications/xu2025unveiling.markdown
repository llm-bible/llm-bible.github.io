---
layout: publication
title: 'Unveiling Downstream Performance Scaling Of Llms: A Clustering-based Perspective'
authors: Chengyin Xu, Kaiyuan Chen, Xiao Li, Ke Shen, Chenggang Li
conference: "Arxiv"
year: 2025
bibkey: xu2025unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.17262"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Pre-Training']
---
The escalating scale and cost of Large Language Models (LLMs) training necessitate accurate pre-training prediction of downstream task performance for efficient resource allocation. This is challenged by: 1) the emergence phenomenon, where metrics become meaningful only after extensive training, hindering prediction by smaller models; and 2) uneven task difficulty and inconsistent performance scaling patterns, leading to high metric variability. Current prediction methods lack accuracy and reliability. We propose a Clustering-On-Difficulty (COD) framework for downstream performance prediction. The COD framework clusters tasks by their difficulty scaling features, thereby establishing a more stable and predictable support subset through the exclusion of tasks exhibiting non-emergent behavior or irregular scaling. We adopt a performance scaling law to predict cluster-wise performance with theoretical support. Predictable subset performance acts as an intermediate predictor for the full evaluation set. We further derive a mapping function to accurately extrapolate the performance of the subset to the full set. Applied to an LLM with 70B parameters, COD achieved a 1.36% average prediction error across eight key LLM benchmarks, offering actionable insights for resource allocation and training monitoring of LLMs pretraining.
