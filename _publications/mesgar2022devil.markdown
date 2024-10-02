---
layout: publication
title: 'The Devil Is In The Details: On Models And Training Regimes For Few-shot Intent Classification'
authors: Mesgar Mohsen, Tran Thy Thy, Glavas Goran, Gurevych Iryna
conference: "Arxiv"
year: 2022
bibkey: mesgar2022devil
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.06440"}
tags: ['Attention Mechanism', 'Few Shot', 'Model Architecture', 'Reinforcement Learning', 'TACL', 'Training Techniques']
---
'Few-shot Intent Classification (FSIC) is one of the key challenges in modular task-oriented dialog systems. While advanced FSIC methods are similar in using pretrained language models to encode texts and nearest neighbour-based inference for classification, these methods differ in details. They start from different pretrained text encoders, use different encoding architectures with varying similarity functions, and adopt different training regimes. Coupling these mostly independent design decisions and the lack of accompanying ablation studies are big obstacle to identify the factors that drive the reported FSIC performance. We study these details across three key dimensions: (1) Encoding architectures: Cross-Encoder vs Bi-Encoders; (2) Similarity function: Parameterized (i.e., trainable) functions vs non-parameterized function; (3) Training regimes: Episodic meta-learning vs the straightforward (i.e., non-episodic) training. Our experimental results on seven FSIC benchmarks reveal three important findings. First, the unexplored combination of the cross-encoder architecture (with parameterized similarity scoring function) and episodic meta-learning consistently yields the best FSIC performance. Second, Episodic training yields a more robust FSIC classifier than non-episodic one. Third, in meta-learning methods, splitting an episode to support and query sets is not a must. Our findings paves the way for conducting state-of-the-art research in FSIC and more importantly raise the community''s attention to details of FSIC methods. We release our code and data publicly.'
