---
layout: publication
title: 'Llava-uhd V2: An MLLM Integrating High-resolution Semantic Pyramid Via Hierarchical Window Transformer'
authors: Yipeng Zhang, Yifan Liu, Zonghao Guo, Yidan Zhang, Xuesong Yang, Xiaoying Zhang, Chi Chen, Jun Song, Bo Zheng, Yuan Yao, Zhiyuan Liu, Tat-seng Chua, Maosong Sun
conference: "Arxiv"
year: 2024
bibkey: zhang2024llava
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.13871'}
tags: ['Attention Mechanism', 'Transformer', 'RAG', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods']
---
Vision transformers (ViTs) are widely employed in multimodal large language
models (MLLMs) for visual encoding. However, they exhibit inferior performance
on tasks regarding fine-grained visual perception. We attribute this to the
limitations of ViTs in capturing diverse multi-modal visual levels, such as
low-level details. To address this issue, we present LLaVA-UHD v2, an MLLM with
advanced perception abilities by introducing a well-designed vision-language
projector, the Hierarchical window (Hiwin) transformer. Hiwin transformer
enhances MLLM's ability to capture diverse multi-modal visual granularities, by
incorporating our constructed high-resolution semantic pyramid. Specifically,
Hiwin transformer comprises two key modules: (i) a visual detail injection
module, which progressively injects low-level visual details into high-level
language-aligned semantics features, thereby forming an inverse semantic
pyramid (ISP), and (ii) a hierarchical window attention module, which leverages
cross-scale windows to condense multi-level semantics from the ISP. Extensive
experiments show that LLaVA-UHD v2 outperforms compared MLLMs on a wide range
of benchmarks. Notably, our design achieves an average boost of 3.7% across 14
benchmarks compared with the baseline method, 9.3% on DocVQA for instance. All
the data and code will be publicly available to facilitate future research.
