---
layout: publication
title: 'MADTP: Multimodal Alignment-guided Dynamic Token Pruning For Accelerating Vision-language Transformer'
authors: Jianjian Cao, Peng Ye, Shengze Li, Chong Yu, Yansong Tang, Jiwen Lu, Tao Chen
conference: "In Proc. IEEE Conference on Computer Vision and Pattern Recognition (CVPR) 2024"
year: 2024
bibkey: cao2024multimodal
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02991"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Multimodal Models', 'Tools', 'Pruning', 'Pretraining Methods', 'Transformer']
---
Vision-Language Transformers (VLTs) have shown great success recently, but
are meanwhile accompanied by heavy computation costs, where a major reason can
be attributed to the large number of visual and language tokens. Existing token
pruning research for compressing VLTs mainly follows a single-modality-based
scheme yet ignores the critical role of aligning different modalities for
guiding the token pruning process, causing the important tokens for one
modality to be falsely pruned in another modality branch. Meanwhile, existing
VLT pruning works also lack the flexibility to dynamically compress each layer
based on different input samples. To this end, we propose a novel framework
named Multimodal Alignment-Guided Dynamic Token Pruning (MADTP) for
accelerating various VLTs. Specifically, we first introduce a well-designed
Multi-modality Alignment Guidance (MAG) module that can align features of the
same semantic concept from different modalities, to ensure the pruned tokens
are less important for all modalities. We further design a novel Dynamic Token
Pruning (DTP) module, which can adaptively adjust the token compression ratio
in each layer based on different input instances. Extensive experiments on
various benchmarks demonstrate that MADTP significantly reduces the
computational complexity of kinds of multimodal models while preserving
competitive performance. Notably, when applied to the BLIP model in the NLVR2
dataset, MADTP can reduce the GFLOPs by 80% with less than 4% performance
degradation.
