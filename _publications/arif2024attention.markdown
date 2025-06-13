---
layout: publication
title: 'Hired: Attention-guided Token Dropping For Efficient Inference Of High-resolution Vision-language Models'
authors: Kazi Hasan Ibn Arif, Jinyi Yoon, Dimitrios S. Nikolopoulos, Hans Vandierendonck, Deepu John, Bo Ji
conference: "Arxiv"
year: 2024
bibkey: arif2024attention
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.10945'}
  - {name: "Code", url: 'https://github.com/hasanar1f/HiRED'}
tags: ['Attention Mechanism', 'Has Code', 'Transformer', 'RAG', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
High-resolution Vision-Language Models (VLMs) are widely used in multimodal
tasks to enhance accuracy by preserving detailed image information. However,
these models often generate an excessive number of visual tokens due to the
need to encode multiple partitions of a high-resolution image input. Processing
such a large number of visual tokens through multiple transformer networks
poses significant computational challenges, particularly for
resource-constrained commodity GPUs. To address this challenge, we propose
High-Resolution Early Dropping (HiRED), a plug-and-play token-dropping method
designed to operate within a fixed token budget. HiRED leverages the attention
of CLS token in the vision transformer (ViT) to assess the visual content of
the image partitions and allocate an optimal token budget for each partition
accordingly. The most informative visual tokens from each partition within the
allocated budget are then selected and passed to the subsequent Large Language
Model (LLM). We showed that HiRED achieves superior accuracy and performance,
compared to existing token-dropping methods. Empirically, HiRED-20% (i.e., a
20% token budget) on LLaVA-Next-7B achieves a 4.7x increase in token generation
throughput, reduces response latency by 78%, and saves 14% of GPU memory for
single inference on an NVIDIA TESLA P40 (24 GB). For larger batch sizes (e.g.,
4), HiRED-20% prevents out-of-memory errors by cutting memory usage by 30%,
while preserving throughput and latency benefits.
  Code - https://github.com/hasanar1f/HiRED
