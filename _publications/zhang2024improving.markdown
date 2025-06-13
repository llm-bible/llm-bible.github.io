---
layout: publication
title: 'GME: Improving Universal Multimodal Retrieval By Multimodal Llms'
authors: Xin Zhang, Yanzhao Zhang, Wen Xie, Mingxin Li, Ziqi Dai, Dingkun Long, Pengjun Xie, Meishan Zhang, Wenjie Li, Min Zhang
conference: "Arxiv"
year: 2024
bibkey: zhang2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.16855'}
tags: ['Multimodal Models', 'Training Techniques', 'Scaling Laws']
---
Universal Multimodal Retrieval (UMR) aims to enable search across various
modalities using a unified model, where queries and candidates can consist of
pure text, images, or a combination of both. Previous work has attempted to
adopt multimodal large language models (MLLMs) to realize UMR using only text
data. However, our preliminary experiments demonstrate that more diverse
multimodal training data can further unlock the potential of MLLMs. Despite its
effectiveness, the existing multimodal training data is highly imbalanced in
terms of modality, which motivates us to develop a training data synthesis
pipeline and construct a large-scale, high-quality fused-modal training
dataset. Based on the synthetic training data, we develop the General
Multimodal Embedder (GME), an MLLM-based dense retriever designed for UMR.
Furthermore, we construct a comprehensive UMR Benchmark (UMRB) to evaluate the
effectiveness of our approach. Experimental results show that our method
achieves state-of-the-art performance among existing UMR methods. Last, we
provide in-depth analyses of model scaling and training strategies, and perform
ablation studies on both the model and synthetic data.
