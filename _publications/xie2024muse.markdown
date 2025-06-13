---
layout: publication
title: 'MUSE-VL: Modeling Unified VLM Through Semantic Discrete Encoding'
authors: Rongchang Xie, Chen Du, Ping Song, Chang Liu
conference: "Arxiv"
year: 2024
bibkey: xie2024muse
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17762"}
tags: ['Training Techniques', 'Multimodal Models']
---
We introduce MUSE-VL, a Unified Vision-Language Model through Semantic
discrete Encoding for multimodal understanding and generation. Recently, the
research community has begun exploring unified models for visual generation and
understanding. However, existing vision tokenizers (e.g., VQGAN) only consider
low-level information, which makes it difficult to align with language tokens.
This results in high training complexity and necessitates a large amount of
training data to achieve optimal performance. Additionally, their performance
is still far from dedicated understanding models. This paper proposes Semantic
Discrete Encoding (SDE), which effectively aligns the information of visual
tokens and language tokens by adding semantic constraints to the visual
tokenizer. This greatly reduces the amount of training data and improves the
performance of the unified model. With the same LLM size, our method improved
the understanding performance by 4.8% compared to the previous SOTA Emu3 and
surpassed the dedicated understanding model LLaVA-NeXT 34B by 3.7%. Our model
also surpasses the existing unified models on visual generation benchmarks.
