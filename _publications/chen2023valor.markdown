---
layout: publication
title: VALOR Vision-audio-language Omni-perception Pretraining Model And Dataset
authors: Chen Sihan, He Xingjian, Guo Longteng, Zhu Xinxin, Wang Weining, Tang Jinhui, Liu Jing
conference: "Arxiv"
year: 2023
bibkey: chen2023valor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.08345"}
  - {name: "Code", url: "https://casia-iva-group.github.io/projects/VALOR"}
tags: ['Applications', 'Has Code', 'Language Modeling', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques']
---
In this paper we propose a Vision-Audio-Language Omni-peRception pretraining model (VALOR) for multi-modal understanding and generation. Different from widely-studied vision-language pretraining models VALOR jointly models relationships of vision audio and language in an end-to-end manner. It contains three separate encoders for single modality representations and a decoder for multimodal conditional text generation. We design two pretext tasks to pretrain VALOR model including Multimodal Grouping Alignment (MGA) and Multimodal Grouping Captioning (MGC). MGA projects vision language and audio to the same common space building vision-language audio-language and audiovisual-language alignment simultaneously. MGC learns how to generate text tokens in conditions of vision audio or their both. To promote vision-audio-language pretraining research we construct a large-scale high-quality tri-modality dataset named VALOR-1M which contains 1M audiable videos with human annotated audiovisual captions. Extensive experiments show that VALOR can learn strong multimodal correlations and be generalized to various downstream tasks (e.g. retrieval captioning and question answering) with different input modalities (e.g. vision-language audio-language and audiovisual-language). VALOR achieves new state-of-the-art performances on series of public cross-modality benchmarks. Code and data are available at project page https://casia-iva-group.github.io/projects/VALOR.
