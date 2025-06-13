---
layout: publication
title: 'Dense Communication Between Language Models'
authors: Shiguang Wu, Yaqing Wang, Quanming Yao
conference: "Arxiv"
year: 2025
bibkey: wu2025dense
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.12741"}
tags: ['Fine-Tuning', 'Training Techniques', 'Efficiency and Optimization', 'Applications']
---
As higher-level intelligence emerges from the combination of modular components with lower-level intelligence, many works combines Large Language Models (LLMs) for collective intelligence. Such combination is achieved by building communications among LLMs. While current systems primarily facilitate such communication through natural language, this paper proposes a novel paradigm of direct dense vector communication between LLMs. Our approach eliminates the unnecessary embedding and de-embedding steps when LLM interact with another, enabling more efficient information transfer, fully differentiable optimization pathways, and exploration of capabilities beyond human heuristics. We use such stripped LLMs as vertexes and optimizable seq2seq modules as edges to construct LMNet, with similar structure as MLPs. By utilizing smaller pre-trained LLMs as vertexes, we train a LMNet that achieves comparable performance with LLMs in similar size with only less than 0.1% training cost. This offers a new perspective on scaling for general intelligence rather than training a monolithic LLM from scratch. Besides, the proposed method can be used for other applications, like customizing LLM with limited data, showing its versatility.
