---
layout: publication
title: 'Towards General Continuous Memory For Vision-language Models'
authors: Wenyi Wu, Zixuan Song, Kun Zhou, Yifei Shao, Zhiting Hu, Biwei Huang
conference: "Arxiv"
year: 2025
bibkey: wu2025towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17670"}
tags: ['Multimodal Models', 'Reinforcement Learning']
---
Language models (LMs) and their extension, vision-language models (VLMs), have achieved remarkable performance across various tasks. However, they still struggle with complex reasoning tasks that require multimodal or multilingual real-world knowledge. To support such capabilities, an external memory system that can efficiently provide relevant multimodal information is essential. Existing approaches generally concatenate image and text tokens into a long sequence as memory, which, however, may drastically increase context length and even degrade performance. In contrast, we propose using continuous memory, a compact set of dense embeddings to more effectively and efficiently represent multimodal and multilingual knowledge. Our key insight is that a VLM can serve as its own continuous memory encoder. We empirically show that this design improves performance on complex multimodal reasoning tasks. Building on this, we introduce a data-efficient and parameter-efficient method to fine-tune the VLM into a memory encoder, requiring only 1.2% of the model's parameters and a small corpus of 15.6K self-synthesized samples. Our approach CoMEM utilizes VLM's original capabilities to encode arbitrary multimodal and multilingual knowledge into just 8 continuous embeddings. Since the inference-time VLM remains frozen, our memory module is plug-and-play and can be flexibly integrated as needed. Extensive experiments across eight multimodal reasoning benchmarks demonstrate the effectiveness of our approach.
