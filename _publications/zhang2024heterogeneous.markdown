---
layout: publication
title: 'Dovetail: A CPU/GPU Heterogeneous Speculative Decoding For LLM Inference'
authors: Libo National University Of Defense Technology, Changsha, China Zhang, Zhaoning National University Of Defense Technology, Changsha, China Zhang, Baizhou National University Of Defense Technology, Changsha, China Xu, Songzhu National University Of Defense Technology, Changsha, China Mei, Dongsheng National University Of Defense Technology, Changsha, China Li
conference: "Arxiv"
year: 2024
bibkey: zhang2024heterogeneous
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.18934"}
tags: ['Efficiency and Optimization', 'Merging']
---
Due to the high resource demands of Large Language Models (LLMs), achieving
widespread deployment on consumer-grade devices presents significant
challenges. Typically, personal or consumer-grade devices, including servers
configured prior to the era of large-scale models, generally have relatively
weak GPUs and relatively strong CPUs. However, most current methods primarily
depend on GPUs for computation. Therefore, we propose Dovetail, an approach
that deploys the draft model on the GPU to generate draft tokens while allowing
the target model to perform parallel verification on the CPU, thereby improving
the utilization of all available hardware resources and occupying less
inter-device communication bandwidth. Accordingly, we have redesigned the draft
model to better align with heterogeneous hardware characteristics. To this end,
we implemented several optimizations: reducing the number of draft tokens to
mitigate latency in parallel verification, increasing the depth of the draft
model to enhance its predictive capacity, and introducing DGF (Dynamic Gating
Fusion) to improve the integration of features and token embeddings. In the
HumanEval benchmark, Dovetail achieved an inference speed of 5.86 tokens per
second for LLaMA2-Chat-7B using 3GB of VRAM, representing an approximately
2.77x improvement over CPU-only inference. Furthermore, the inference speed was
increased to 8 tokens per second when utilizing 7GB of VRAM.
