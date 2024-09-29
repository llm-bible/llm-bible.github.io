---
layout: publication
title: Mg45;llava Towards Multi45;granularity Visual Instruction Tuning
authors: Zhao Xiangyu, Li Xiangtai, Duan Haodong, Huang Haian, Li Yining, Chen Kai, Yang Hua
conference: "Arxiv"
year: 2024
bibkey: zhao2024mg
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17770"}
  - {name: "Code", url: "https://github.com/PhoenixZ810/MG&#45;LLaVA"}
tags: ['Has Code', 'Merging', 'Multimodal Models']
---
Multi45;modal large language models (MLLMs) have made significant strides in various visual understanding tasks. However the majority of these models are constrained to process low45;resolution images which limits their effectiveness in perception tasks that necessitate detailed visual information. In our study we present MG45;LLaVA an innovative MLLM that enhances the models visual processing capabilities by incorporating a multi45;granularity vision flow which includes low45;resolution high45;resolution and object45;centric features. We propose the integration of an additional high45;resolution visual encoder to capture fine45;grained details which are then fused with base visual features through a Conv45;Gate fusion network. To further refine the models object recognition abilities we incorporate object45;level features derived from bounding boxes identified by offline detectors. Being trained solely on publicly available multimodal data through instruction tuning MG45;LLaVA demonstrates exceptional perception skills. We instantiate MG45;LLaVA with a wide variety of language encoders ranging from 3.8B to 34B to evaluate the models performance comprehensively. Extensive evaluations across multiple benchmarks demonstrate that MG45;LLaVA outperforms existing MLLMs of comparable parameter sizes showcasing its remarkable efficacy. The code will be available at https://github.com/PhoenixZ810/MG&#45;LLaVA.
