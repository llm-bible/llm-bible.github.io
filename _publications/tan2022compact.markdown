---
layout: publication
title: 'ACORT: A Compact Object Relation Transformer For Parameter Efficient Image Captioning'
authors: Tan Jia Huei, Tan Ying Hua, Chan Chee Seng, Chuah Joon Huang
conference: "Arxiv"
year: 2022
bibkey: tan2022compact
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.05451"}
  - {name: "Code", url: "https://github.com/jiahuei/sparse-image-captioning"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Recent research that applies Transformer-based architectures to image captioning has resulted in state-of-the-art image captioning performance, capitalising on the success of Transformers on natural language tasks. Unfortunately, though these models work well, one major flaw is their large model sizes. To this end, we present three parameter reduction methods for image captioning Transformers: Radix Encoding, cross-layer parameter sharing, and attention parameter sharing. By combining these methods, our proposed ACORT models have 3.7x to 21.6x fewer parameters than the baseline model without compromising test performance. Results on the MS-COCO dataset demonstrate that our ACORT models are competitive against baselines and SOTA approaches, with CIDEr score >=126. Finally, we present qualitative results and ablation studies to demonstrate the efficacy of the proposed changes further. Code and pre-trained models are publicly available at https://github.com/jiahuei/sparse-image-captioning.
