---
layout: publication
title: 'Language-image Alignment With Fixed Text Encoders'
authors: Jingfeng Yang, Ziyang Wu, Yue Zhao, Yi Ma
conference: "Arxiv"
year: 2025
bibkey: yang2025language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.04209"}
tags: ['Pretraining Methods', 'Efficiency and Optimization', 'Training Techniques', 'Tools']
---
Currently, the most dominant approach to establishing language-image alignment is to pre-train text and image encoders jointly through contrastive learning, such as CLIP and its variants. In this work, we question whether such a costly joint training is necessary. In particular, we investigate if a pre-trained fixed large language model (LLM) offers a good enough text encoder to guide visual representation learning. That is, we propose to learn Language-Image alignment with a Fixed Text encoder (LIFT) from an LLM by training only the image encoder. Somewhat surprisingly, through comprehensive benchmarking and ablation studies, we find that this much simplified framework LIFT is highly effective and it outperforms CLIP in most scenarios that involve compositional understanding and long captions, while achieving considerable gains in computational efficiency. Our work takes a first step towards systematically exploring how text embeddings from LLMs can guide visual learning and suggests an alternative design choice for learning language-aligned visual representations.
