---
layout: publication
title: Video-lavit: Unified Video-language Pre-training With Decoupled Visual-motional Tokenization
authors: Jin Yang, Sun Zhicheng, Xu Kun, Xu Kun, Chen Liwei, Jiang Hao, Huang Quzhe, Song Chengru, Liu Yuliang, Zhang Di, Song Yang, Gai Kun, Mu Yadong
conference: "Arxiv"
year: 2024
bibkey: jin2024video
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03161"}
  - {name: "Code", url: "https://video-lavit.github.io"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Tokenization', 'Tools', 'Training Techniques']
---
In light of recent advances in multimodal Large Language Models (LLMs) there is increasing attention to scaling them from image-text data to more informative real-world videos. Compared to static images video poses unique challenges for effective large-scale pre-training due to the modeling of its spatiotemporal dynamics. In this paper we address such limitations in video-language pre-training with an efficient video decomposition that represents each video as keyframes and temporal motions. These are then adapted to an LLM using well-designed tokenizers that discretize visual and temporal information as a few tokens thus enabling unified generative pre-training of videos images and text. At inference the generated tokens from the LLM are carefully recovered to the original continuous pixel space to create various video content. Our proposed framework is both capable of comprehending and generating image and video content as demonstrated by its competitive performance across 13 multimodal benchmarks in image and video understanding and generation. Our code and models are available at https://video-lavit.github.io."
