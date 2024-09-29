---
layout: publication
title: CLAMP&#58; Contrastive Language Model Prompt-tuning
authors: Teterwak Piotr, Sun Ximeng, Plummer Bryan A., Saenko Kate, Lim Ser-nam
conference: "Arxiv"
year: 2023
bibkey: teterwak2023contrastive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.01629"}
tags: ['Applications', 'Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have emerged as powerful general-purpose interfaces for many machine learning problems. Recent work has adapted LLMs to generative visual tasks like image captioning visual question answering and visual chat using a relatively small amount of instruction-tuning data. In this paper we explore whether modern LLMs can also be adapted to classifying an image into a set of categories. First we evaluate multimodal LLMs that are tuned for generative tasks on zero-shot image classification and find that their performance is far below that of specialized models like CLIP. We then propose an approach for light fine-tuning of LLMs using the same contrastive image-caption matching objective as CLIP. Our results show that LLMs can indeed achieve good image classification performance when adapted this way. Our approach beats state-of-the-art mLLMs by 1337; and slightly outperforms contrastive learning with a custom text model while also retaining the LLMs generative abilities. LLM initialization appears to particularly help classification in domains under-represented in the visual pre-training data.
