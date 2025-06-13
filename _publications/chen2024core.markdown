---
layout: publication
title: 'Core Context Aware Transformers For Long Context Language Modeling'
authors: Yaofo Chen, Zeng You, Shuhai Zhang, Haokun Li, Yirui Li, Yaowei Wang, Mingkui Tan
conference: "Arxiv"
year: 2024
bibkey: chen2024core
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.12465"}
tags: ['Fine-Tuning', 'Transformer', 'Efficiency and Optimization', 'RAG', 'Model Architecture', 'Language Modeling', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
Transformer-based Large Language Models (LLMs) have exhibited remarkable success in extensive tasks primarily attributed to self-attention mechanism, which requires a token to consider all preceding tokens as its context to compute attention. However, when the context length L becomes very large (e.g., 128K), the amount of potentially redundant information in the context tends to increase. The redundant context not only hampers the modeling representation performance but also incurs unnecessary computational and storage overhead. In this paper, we propose a plug-and-play Core Context Aware (CCA) Attention for efficient long-context modeling, comprising two complementary modules: 1) Globality-aware pooling module groups input tokens and dynamically compresses each group into one core token based on their significance. In this way, our method automatically focuses and strengthens core context while diminishing redundancy during the learning process, leading to effective long-term dependency modeling. 2) Locality-preserving module incorporates neighboring tokens to preserve local context for detailed representation. Notably, our CCA-Attention is able to replace the self-attention module in existing LLMs with minimal fine-tuning cost. Extensive experimental results show the superiority of our method in both long-context modeling and computational efficiency over state-of-the-art methods.
