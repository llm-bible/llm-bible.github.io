---
layout: publication
title: 'Diffusion Vs. Autoregressive Language Models: A Text Embedding Perspective'
authors: Siyue Zhang, Yilun Zhao, Liyuan Geng, Arman Cohan, Anh Tuan Luu, Chen Zhao
conference: "Arxiv"
year: 2025
bibkey: zhang2025diffusion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15045"}
tags: ['Training Techniques', 'Model Architecture', 'Merging', 'GPT', 'Pretraining Methods', 'BERT', 'Pre-Training', 'Attention Mechanism']
---
Large language model (LLM)-based embedding models, benefiting from large scale pre-training and post-training, have begun to surpass BERT and T5-based models on general-purpose text embedding tasks such as document retrieval. However, a fundamental limitation of LLM embeddings lies in the unidirectional attention used during autoregressive pre-training, which misaligns with the bidirectional nature of text embedding tasks. To this end, We propose adopting diffusion language models for text embeddings, motivated by their inherent bidirectional architecture and recent success in matching or surpassing LLMs especially on reasoning tasks. We present the first systematic study of the diffusion language embedding model, which outperforms the LLM-based embedding model by 20% on long-document retrieval, 8% on reasoning-intensive retrieval, 2% on instruction-following retrieval, and achieve competitive performance on traditional text embedding benchmarks. Our analysis verifies that bidirectional attention is crucial for encoding global context in long and complex text.
