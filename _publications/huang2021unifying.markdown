---
layout: publication
title: Unifying Multimodal Transformer For Bi45;directional Image And Text Generation
authors: Huang Yupan, Xue Hongwei, Liu Bei, Lu Yutong
conference: "Arxiv"
year: 2021
bibkey: huang2021unifying
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2110.09753"}
tags: ['Applications', 'Language Modeling', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
We study the joint learning of image45;to45;text and text45;to45;image generations which are naturally bi45;directional tasks. Typical existing works design two separate task45;specific models for each task which impose expensive design efforts. In this work we propose a unified image45;and45;text generative framework based on a single multimodal model to jointly study the bi45;directional tasks. We adopt Transformer as our unified architecture for its strong performance and task45;agnostic design. Specifically we formulate both tasks as sequence generation tasks where we represent images and text as unified sequences of tokens and the Transformer learns multimodal interactions to generate sequences. We further propose two45;level granularity feature representations and sequence45;level training to improve the Transformer45;based unified framework. Experiments show that our approach significantly improves previous Transformer45;based model X45;LXMERTs FID from 37.0 to 29.9 (lower is better) for text45;to45;image generation and improves CIDEr45;D score from 100.937; to 122.637; for fine45;tuned image45;to45;text generation on the MS45;COCO dataset. Our code is available online.
