---
layout: publication
title: Longllava Scaling Multi-modal Llms To 1000 Images Efficiently Via Hybrid Architecture
authors: Wang Xidong, Song Dingjie, Chen Shunian, Zhang Chen, Wang Benyou
conference: "Arxiv"
year: 2024
bibkey: wang2024longllava
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.02889"}
tags: ['Agentic', 'Efficiency And Optimization', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques', 'Transformer']
---
Expanding the long-context capabilities of Multi-modal Large Language Models~(MLLMs) is crucial for video understanding high-resolution image understanding and multi-modal agents. This involves a series of systematic optimizations including model architecture data construction and training strategy particularly addressing challenges such as and . In this paper we adapt the model architecture to a hybrid of Mamba and Transformer blocks approach data construction with both temporal and spatial dependencies among multiple images and employ a progressive training strategy. The released model ~(-Context arge anguage nd ision ssistant) is the first hybrid MLLM which achieved a better balance between efficiency and effectiveness. LongLLaVA not only achieves competitive results across various benchmarks but also maintains high throughput and low memory consumption. Especially it could process nearly a thousand images on a single A100 80GB GPU showing promising application prospects for a wide range of tasks.
