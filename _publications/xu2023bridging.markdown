---
layout: publication
title: 'Bridging Vision And Language Encoders: Parameter-efficient Tuning For Referring
  Image Segmentation'
authors: Zunnan Xu et al.
conference: Arxiv
year: 2023
citations: 36
bibkey: xu2023bridging
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2307.11545'}, {name: Code,
    url: 'https://github.com/kkakkkka/ETRIS'}]
tags: [Multimodal Models]
---
Parameter Efficient Tuning (PET) has gained attention for reducing the number
of parameters while maintaining performance and providing better hardware
resource savings, but few studies investigate dense prediction tasks and
interaction between modalities. In this paper, we do an investigation of
efficient tuning problems on referring image segmentation. We propose a novel
adapter called Bridger to facilitate cross-modal information exchange and
inject task-specific information into the pre-trained model. We also design a
lightweight decoder for image segmentation. Our approach achieves comparable or
superior performance with only 1.61% to 3.38% backbone parameter updates,
evaluated on challenging benchmarks. The code is available at
https://github.com/kkakkkka/ETRIS.