---
layout: publication
title: 'Egovlpv2: Egocentric Video-language Pre-training With Fusion In The Backbone'
authors: Shraman Pramanick et al.
conference: Arxiv
year: 2023
citations: 34
bibkey: pramanick2023egocentric
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.05463'}, {name: Code,
    url: 'https://shramanpramanick.github.io/EgoVLPv2/'}]
tags: [Multimodal Models, Pre-Training, Fine-Tuning, Model Architecture, Attention
    Mechanism]
---
Video-language pre-training (VLP) has become increasingly important due to
its ability to generalize to various vision and language tasks. However,
existing egocentric VLP frameworks utilize separate video and language encoders
and learn task-specific cross-modal information only during fine-tuning,
limiting the development of a unified system. In this work, we introduce the
second generation of egocentric video-language pre-training (EgoVLPv2), a
significant improvement from the previous generation, by incorporating
cross-modal fusion directly into the video and language backbones. EgoVLPv2
learns strong video-text representation during pre-training and reuses the
cross-modal attention modules to support different downstream tasks in a
flexible and efficient manner, reducing fine-tuning costs. Moreover, our
proposed fusion in the backbone strategy is more lightweight and
compute-efficient than stacking additional fusion-specific layers. Extensive
experiments on a wide range of VL tasks demonstrate the effectiveness of
EgoVLPv2 by achieving consistent state-of-the-art performance over strong
baselines across all downstream. Our project page can be found at
https://shramanpramanick.github.io/EgoVLPv2/.