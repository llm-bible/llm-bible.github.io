---
layout: publication
title: Boosting Continual Learning Of Vision-language Models Via Mixture-of-experts
  Adapters
authors: Jiazuo Yu et al.
conference: Arxiv
year: 2024
citations: 17
bibkey: yu2024boosting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.11549'}, {name: Code,
    url: 'https://github.com/JiazuoYu/MoE-Adapters4CL'}]
tags: [Tools, Multimodal Models]
---
Continual learning can empower vision-language models to continuously acquire
new knowledge, without the need for access to the entire historical dataset.
However, mitigating the performance degradation in large-scale models is
non-trivial due to (i) parameter shifts throughout lifelong learning and (ii)
significant computational burdens associated with full-model tuning. In this
work, we present a parameter-efficient continual learning framework to
alleviate long-term forgetting in incremental learning with vision-language
models. Our approach involves the dynamic expansion of a pre-trained CLIP
model, through the integration of Mixture-of-Experts (MoE) adapters in response
to new tasks. To preserve the zero-shot recognition capability of
vision-language models, we further introduce a Distribution Discriminative
Auto-Selector (DDAS) that automatically routes in-distribution and
out-of-distribution inputs to the MoE Adapter and the original CLIP,
respectively. Through extensive experiments across various settings, our
proposed method consistently outperforms previous state-of-the-art approaches
while concurrently reducing parameter training burdens by 60%. Our code locates
at https://github.com/JiazuoYu/MoE-Adapters4CL