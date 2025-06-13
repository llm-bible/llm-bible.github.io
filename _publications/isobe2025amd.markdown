---
layout: publication
title: 'Amd-hummingbird: Towards An Efficient Text-to-video Model'
authors: Takashi Isobe, He Cui, Dong Zhou, Mengmeng Ge, Dong Li, Emad Barsoum
conference: "Arxiv"
year: 2025
bibkey: isobe2025amd
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.18559"}
tags: ['Tools', 'Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Reinforcement Learning', 'Training Techniques', 'Attention Mechanism', 'Prompting']
---
Text-to-Video (T2V) generation has attracted significant attention for its
ability to synthesize realistic videos from textual descriptions. However,
existing models struggle to balance computational efficiency and high visual
quality, particularly on resource-limited devices, e.g.,iGPUs and mobile
phones. Most prior work prioritizes visual fidelity while overlooking the need
for smaller, more efficient models suitable for real-world deployment. To
address this challenge, we propose a lightweight T2V framework, termed
Hummingbird, which prunes existing models and enhances visual quality through
visual feedback learning. Our approach reduces the size of the U-Net from 1.4
billion to 0.7 billion parameters, significantly improving efficiency while
preserving high-quality video generation. Additionally, we introduce a novel
data processing pipeline that leverages Large Language Models (LLMs) and Video
Quality Assessment (VQA) models to enhance the quality of both text prompts and
video data. To support user-driven training and style customization, we
publicly release the full training code, including data processing and model
training. Extensive experiments show that our method achieves a 31X speedup
compared to state-of-the-art models such as VideoCrafter2, while also attaining
the highest overall score on VBench. Moreover, our method supports the
generation of videos with up to 26 frames, addressing the limitations of
existing U-Net-based methods in long video generation. Notably, the entire
training process requires only four GPUs, yet delivers performance competitive
with existing leading methods. Hummingbird presents a practical and efficient
solution for T2V generation, combining high performance, scalability, and
flexibility for real-world applications.
