---
layout: publication
title: 'Calibquant: 1-bit KV Cache Quantization For Multimodal Llms'
authors: Insu Han, Zeliang Zhang, Zhiyuan Wang, Yifan Zhu, Susan Liang, Jiani Liu, Haiting Lin, Mingjie Zhao, Chenliang Xu, Kun Wan, Wentian Zhao
conference: "Arxiv"
year: 2025
bibkey: han2025kv
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.14882"}
  - {name: "Code", url: "https://github.com/insuhan/calibquant"}
tags: ['Efficiency and Optimization', 'Applications', 'RAG', 'Has Code', 'Multimodal Models', 'Quantization']
---
Multimodal Large Language Models (MLLMs) have demonstrated remarkable
performance across diverse applications. However, their computational overhead
during deployment remains a critical bottleneck. While Key-Value (KV) caching
effectively trades memory for computation to enhance inference efficiency, the
growing memory footprint from extensive KV caches significantly reduces
throughput and restricts prolonged deployment on memory-constrained GPU
devices. To address this challenge, we propose CalibQuant, a simple yet highly
effective visual quantization strategy that drastically reduces both memory and
computational overhead. Specifically, CalibQuant introduces an extreme 1-bit
quantization scheme, complemented by novel post-scaling and calibration
techniques tailored to the intrinsic patterns of KV caches, thereby ensuring
high efficiency without compromising model performance. Leveraging Triton for
runtime optimization, we achieve a 10x throughput increase on InternVL models.
Our method is designed to be plug-and-play, seamlessly integrating with various
existing MLLMs without requiring architectural changes. Extensive experiments
confirm that our approach significantly reduces memory usage while maintaining
computational efficiency and preserving multimodal capabilities. Codes are
available at https://github.com/insuhan/calibquant.
