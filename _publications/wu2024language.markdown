---
layout: publication
title: 'Liquid: Language Models Are Scalable And Unified Multi-modal Generators'
authors: Junfeng Wu, Yi Jiang, Chuofan Ma, Yuliang Liu, Hengshuang Zhao, Zehuan Yuan, Song Bai, Xiang Bai
conference: "Arxiv"
year: 2024
bibkey: wu2024language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.04332"}
  - {name: "Code", url: "https://github.com/FoundationVision/Liquid"}
tags: ['Training Techniques', 'Multimodal Models', 'Has Code', 'Reinforcement Learning']
---
We present Liquid, an auto-regressive generation paradigm that seamlessly
integrates visual comprehension and generation by tokenizing images into
discrete codes and learning these code embeddings alongside text tokens within
a shared feature space for both vision and language. Unlike previous multimodal
large language model (MLLM), Liquid achieves this integration using a single
large language model (LLM), eliminating the need for external pretrained visual
embeddings such as CLIP. For the first time, Liquid uncovers a scaling law that
performance drop unavoidably brought by the unified training of visual and
language tasks diminishes as the model size increases. Furthermore, the unified
token space enables visual generation and comprehension tasks to mutually
enhance each other, effectively removing the typical interference seen in
earlier models. We show that existing LLMs can serve as strong foundations for
Liquid, saving 100x in training costs while outperforming Chameleon in
multimodal capabilities and maintaining language performance comparable to
mainstream LLMs like LLAMA2. Liquid also outperforms models like SD v2.1 and
SD-XL (FID of 5.47 on MJHQ-30K), excelling in both vision-language and
text-only tasks. This work demonstrates that LLMs such as Qwen2.5 and GEMMA2
are powerful multimodal generators, offering a scalable solution for enhancing
both vision-language understanding and generation. The code and models will be
released at https://github.com/FoundationVision/Liquid.
