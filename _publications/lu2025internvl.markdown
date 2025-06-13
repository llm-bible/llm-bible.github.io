---
layout: publication
title: 'Internvl-x: Advancing And Accelerating Internvl Series With Efficient Visual Token Compression'
authors: Dongchen Lu, Yuyao Sun, Zilu Zhang, Leping Huang, Jianliang Zeng, Mao Shu, Huo Cao
conference: "Arxiv"
year: 2025
bibkey: lu2025internvl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.21307"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'RAG', 'Attention Mechanism']
---
Most multimodal large language models (MLLMs) treat visual tokens as "a
sequence of text", integrating them with text tokens into a large language
model (LLM). However, a great quantity of visual tokens significantly increases
the demand for computational resources and time. In this paper, we propose
InternVL-X, which outperforms the InternVL model in both performance and
efficiency by incorporating three visual token compression methods. First, we
propose a novel vision-language projector, PVTC. This component integrates
adjacent visual embeddings to form a local query and utilizes the transformed
CLS token as a global query, then performs point-to-region cross-attention
through these local and global queries to more effectively convert visual
features. Second, we present a layer-wise visual token compression module,
LVTC, which compresses tokens in the LLM shallow layers and then expands them
through upsampling and residual connections in the deeper layers. This
significantly enhances the model computational efficiency. Futhermore, we
propose an efficient high resolution slicing method, RVTC, which dynamically
adjusts the number of visual tokens based on image area or length filtering.
RVTC greatly enhances training efficiency with only a slight reduction in
performance. By utilizing 20% or fewer visual tokens, InternVL-X achieves
state-of-the-art performance on 7 public MLLM benchmarks, and improves the
average metric by 2.34% across 12 tasks.
