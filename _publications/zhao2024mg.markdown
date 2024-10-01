---
layout: publication
title: 'Mg-llava: Towards Multi-granularity Visual Instruction Tuning'
authors: Zhao Xiangyu, Li Xiangtai, Duan Haodong, Huang Haian, Li Yining, Chen Kai, Yang Hua
conference: "Arxiv"
year: 2024
bibkey: zhao2024mg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17770"}
  - {name: "Code", url: "https://github.com/PhoenixZ810/MG-LLaVA"}
tags: ['Has Code', 'Merging', 'Multimodal Models']
---
"Multi-modal large language models (MLLMs) have made significant strides in various visual understanding tasks. However, the majority of these models are constrained to process low-resolution images, which limits their effectiveness in perception tasks that necessitate detailed visual information. In our study, we present MG-LLaVA, an innovative MLLM that enhances the model's visual processing capabilities by incorporating a multi-granularity vision flow, which includes low-resolution, high-resolution, and object-centric features. We propose the integration of an additional high-resolution visual encoder to capture fine-grained details, which are then fused with base visual features through a Conv-Gate fusion network. To further refine the model's object recognition abilities, we incorporate object-level features derived from bounding boxes identified by offline detectors. Being trained solely on publicly available multimodal data through instruction tuning, MG-LLaVA demonstrates exceptional perception skills. We instantiate MG-LLaVA with a wide variety of language encoders, ranging from 3.8B to 34B, to evaluate the model's performance comprehensively. Extensive evaluations across multiple benchmarks demonstrate that MG-LLaVA outperforms existing MLLMs of comparable parameter sizes, showcasing its remarkable efficacy. The code will be available at https://github.com/PhoenixZ810/MG-LLaVA."
