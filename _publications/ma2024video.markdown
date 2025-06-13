---
layout: publication
title: 'Video Token Sparsification For Efficient Multimodal Llms In Autonomous Driving'
authors: Yunsheng Ma, Amr Abdelraouf, Rohit Gupta, Ziran Wang, Kyungtae Han
conference: "Arxiv"
year: 2024
bibkey: ma2024video
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.11182"}
tags: ['RAG', 'Pruning', 'Multimodal Models']
---
Multimodal large language models (MLLMs) have demonstrated remarkable
potential for enhancing scene understanding in autonomous driving systems
through powerful logical reasoning capabilities. However, the deployment of
these models faces significant challenges due to their substantial parameter
sizes and computational demands, which often exceed the constraints of onboard
computation. One major limitation arises from the large number of visual tokens
required to capture fine-grained and long-context visual information, leading
to increased latency and memory consumption. To address this issue, we propose
Video Token Sparsification (VTS), a novel approach that leverages the inherent
redundancy in consecutive video frames to significantly reduce the total number
of visual tokens while preserving the most salient information. VTS employs a
lightweight CNN-based proposal model to adaptively identify key frames and
prune less informative tokens, effectively mitigating hallucinations and
increasing inference throughput without compromising performance. We conduct
comprehensive experiments on the DRAMA and LingoQA benchmarks, demonstrating
the effectiveness of VTS in achieving up to a 33% improvement in inference
throughput and a 28% reduction in memory usage compared to the baseline
without compromising performance.
