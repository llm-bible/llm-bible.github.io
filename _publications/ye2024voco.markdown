---
layout: publication
title: 'Voco-llama: Towards Vision Compression With Large Language Models'
authors: Xubing Ye, Yukang Gan, Xiaoke Huang, Yixiao Ge, Yansong Tang
conference: "Arxiv"
year: 2024
bibkey: ye2024voco
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12275"}
  - {name: "Code", url: "https://yxxxb.github.io/VoCo-LLaMA-page/"}
tags: ['Efficiency and Optimization', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Has Code', 'Multimodal Models', 'Distillation']
---
Vision-Language Models (VLMs) have achieved remarkable success in various
multi-modal tasks, but they are often bottlenecked by the limited context
window and high computational cost of processing high-resolution image inputs
and videos. Vision compression can alleviate this problem by reducing the
vision token count. Previous approaches compress vision tokens with external
modules and force LLMs to understand the compressed ones, leading to visual
information loss. However, the LLMs' understanding paradigm of vision tokens is
not fully utilised in the compression learning process. We propose VoCo-LLaMA,
the first approach to compress vision tokens using LLMs. By introducing Vision
Compression tokens during the vision instruction tuning phase and leveraging
attention distillation, our method distill how LLMs comprehend vision tokens
into their processing of VoCo tokens. VoCo-LLaMA facilitates effective vision
compression and improves the computational efficiency during the inference
stage. Specifically, our method achieves minimal performance loss with a
compression ratio of 576\\(\times\\), resulting in up to 94.8\\(%\\) fewer FLOPs and
69.6\\(%\\) acceleration in inference time. Furthermore, through continuous
training using time-series compressed token sequences of video frames,
VoCo-LLaMA demonstrates the ability to understand temporal correlations,
outperforming previous methods on popular video question-answering benchmarks.
Our approach presents a promising way to unlock the full potential of VLMs'
contextual window, enabling more scalable multi-modal applications. The project
page, along with the associated code, can be accessed via
https://yxxxb.github.io/VoCo-LLaMA-page/.
