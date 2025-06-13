---
layout: publication
title: 'Swap Attention In Spatiotemporal Diffusions For Text-to-video Generation'
authors: Wenjing Wang, Huan Yang, Zixi Tuo, Huiguo He, Junchen Zhu, Jianlong Fu, Jiaying Liu
conference: "Arxiv"
year: 2023
bibkey: wang2023swap
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.10874'}
tags: ['Attention Mechanism', 'Transformer', 'Model Architecture', 'Merging', 'Reinforcement Learning']
---
With the explosive popularity of AI-generated content (AIGC), video
generation has recently received a lot of attention. Generating videos guided
by text instructions poses significant challenges, such as modeling the complex
relationship between space and time, and the lack of large-scale text-video
paired data. Existing text-video datasets suffer from limitations in both
content quality and scale, or they are not open-source, rendering them
inaccessible for study and use. For model design, previous approaches extend
pretrained text-to-image generation models by adding temporal 1D
convolution/attention modules for video generation. However, these approaches
overlook the importance of jointly modeling space and time, inevitably leading
to temporal distortions and misalignment between texts and videos. In this
paper, we propose a novel approach that strengthens the interaction between
spatial and temporal perceptions. In particular, we utilize a swapped
cross-attention mechanism in 3D windows that alternates the "query" role
between spatial and temporal blocks, enabling mutual reinforcement for each
other. Moreover, to fully unlock model capabilities for high-quality video
generation and promote the development of the field, we curate a large-scale
and open-source video dataset called HD-VG-130M. This dataset comprises 130
million text-video pairs from the open-domain, ensuring high-definition,
widescreen and watermark-free characters. A smaller-scale yet more meticulously
cleaned subset further enhances the data quality, aiding models in achieving
superior performance. Experimental quantitative and qualitative results
demonstrate the superiority of our approach in terms of per-frame quality,
temporal correlation, and text-video alignment, with clear margins.
