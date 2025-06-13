---
layout: publication
title: 'Free Video-llm: Prompt-guided Visual Perception For Efficient Training-free Video Llms'
authors: Kai Han, Jianyuan Guo, Yehui Tang, Wei He, Enhua Wu, Yunhe Wang
conference: "Arxiv"
year: 2024
bibkey: han2024free
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.10441"}
  - {name: "Code", url: "https://github.com/contrastive/FreeVideoLLM"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Multimodal Models', 'Tools', 'Has Code', 'Prompting']
---
Vision-language large models have achieved remarkable success in various
multi-modal tasks, yet applying them to video understanding remains challenging
due to the inherent complexity and computational demands of video data. While
training-based video-LLMs deliver high performance, they often require
substantial resources for training and inference. Conversely, training-free
approaches offer a more efficient alternative by adapting pre-trained
image-LLMs models for video tasks without additional training, but they face
inference efficiency bottlenecks due to the large number of visual tokens
generated from video frames. In this work, we present a novel prompt-guided
visual perception framework (abbreviated as Free Video-LLM) for efficient
inference of training-free video LLMs. The proposed framework decouples
spatial-temporal dimension and performs temporal frame sampling and spatial RoI
cropping respectively based on task-specific prompts. Our method effectively
reduces the number of visual tokens while maintaining high performance across
multiple video question-answering benchmarks. Extensive experiments demonstrate
that our approach achieves competitive results with significantly fewer tokens,
offering an optimal trade-off between accuracy and computational efficiency
compared to state-of-the-art video LLMs. The code will be available at
https://github.com/contrastive/FreeVideoLLM.
