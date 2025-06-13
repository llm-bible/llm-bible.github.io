---
layout: publication
title: 'Cross-modal RAG: Sub-dimensional Retrieval-augmented Text-to-image Generation'
authors: Mengdan Zhu, Senhao Cheng, Guangji Bai, Yifei Zhang, Liang Zhao
conference: "Arxiv"
year: 2025
bibkey: zhu2025cross
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.21956"}
tags: ['RAG', 'Tools', 'Multimodal Models', 'Efficiency and Optimization']
---
Text-to-image generation increasingly demands access to domain-specific, fine-grained, and rapidly evolving knowledge that pretrained models cannot fully capture. Existing Retrieval-Augmented Generation (RAG) methods attempt to address this by retrieving globally relevant images, but they fail when no single image contains all desired elements from a complex user query. We propose Cross-modal RAG, a novel framework that decomposes both queries and images into sub-dimensional components, enabling subquery-aware retrieval and generation. Our method introduces a hybrid retrieval strategy - combining a sub-dimensional sparse retriever with a dense retriever - to identify a Pareto-optimal set of images, each contributing complementary aspects of the query. During generation, a multimodal large language model is guided to selectively condition on relevant visual features aligned to specific subqueries, ensuring subquery-aware image synthesis. Extensive experiments on MS-COCO, Flickr30K, WikiArt, CUB, and ImageNet-LT demonstrate that Cross-modal RAG significantly outperforms existing baselines in both retrieval and generation quality, while maintaining high efficiency.
