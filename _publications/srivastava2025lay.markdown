---
layout: publication
title: 'Lay-your-scene: Natural Scene Layout Generation With Diffusion Transformers'
authors: Divyansh Srivastava, Xiang Zhang, He Wen, Chenru Wen, Zhuowen Tu
conference: "Arxiv"
year: 2025
bibkey: srivastava2025lay
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.04718"}
tags: ['Model Architecture', 'Merging', 'Pretraining Methods', 'Transformer', 'Prompting', 'Applications']
---
We present Lay-Your-Scene (shorthand LayouSyn), a novel text-to-layout
generation pipeline for natural scenes. Prior scene layout generation methods
are either closed-vocabulary or use proprietary large language models for
open-vocabulary generation, limiting their modeling capabilities and broader
applicability in controllable image generation. In this work, we propose to use
lightweight open-source language models to obtain scene elements from text
prompts and a novel aspect-aware diffusion Transformer architecture trained in
an open-vocabulary manner for conditional layout generation. Extensive
experiments demonstrate that LayouSyn outperforms existing methods and achieves
state-of-the-art performance on challenging spatial and numerical reasoning
benchmarks. Additionally, we present two applications of LayouSyn. First, we
show that coarse initialization from large language models can be seamlessly
combined with our method to achieve better results. Second, we present a
pipeline for adding objects to images, demonstrating the potential of LayouSyn
in image editing applications.
