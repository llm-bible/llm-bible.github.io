---
layout: publication
title: Tokenpacker Efficient Visual Projector For Multimodal LLM
authors: Li Wentong, Yuan Yuqian, Liu Jian, Tang Dongqi, Wang Song, Qin Jie, Zhu Jianke, Zhang Lei
conference: "Arxiv"
year: 2024
bibkey: li2024tokenpacker
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.02392"}
  - {name: "Code", url: "https://github.com/CircleRadon/TokenPacker"}
tags: ['Efficiency And Optimization', 'Has Code', 'Multimodal Models']
---
The visual projector serves as an essential bridge between the visual encoder and the Large Language Model (LLM) in a Multimodal LLM (MLLM). Typically MLLMs adopt a simple MLP to preserve all visual contexts via one-to-one transformation. However the visual tokens are redundant and can be considerably increased when dealing with high-resolution images impairing the efficiency of MLLMs significantly. Some recent works have introduced resampler or abstractor to reduce the number of resulting visual tokens. Unfortunately they fail to capture finer details and undermine the visual reasoning capabilities of MLLMs. In this work we propose a novel visual projector which adopts a coarse-to-fine scheme to inject the enriched characteristics to generate the condensed visual tokens. In specific we first interpolate the visual features as a low-resolution point query providing the overall visual representation as the foundation. Then we introduce a region-to-point injection module that utilizes high-resolution multi-level region-based cues as fine-grained reference keys and values allowing them to be fully absorbed within the corresponding local context region. This step effectively updates the coarse point query transforming it into an enriched one for the subsequent LLM reasoning. Extensive experiments demonstrate that our approach compresses the visual tokens by 7537;~8937; while achieves comparable or even better performance across diverse benchmarks with significantly higher efficiency. The source codes can be found at https://github.com/CircleRadon/TokenPacker.
