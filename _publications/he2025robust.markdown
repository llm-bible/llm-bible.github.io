---
layout: publication
title: 'Desclip: Robust Continual Adaptation Via General Attribute Descriptions For Pretrained Vision-language Models'
authors: Chiyuan He, Zihuan Qiu, Fanman Meng, Linfeng Xu, Qingbo Wu, Hongliang Li
conference: "Arxiv"
year: 2025
bibkey: he2025robust
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.00618'}
tags: ['Reinforcement Learning', 'RAG', 'Multimodal Models', 'Prompting']
---
Continual adaptation of vision-language models (VLMs) focuses on leveraging
cross-modal pretrained knowledge to incrementally adapt for expanding
downstream tasks and datasets, while tackling the challenge of knowledge
forgetting. Existing research often focuses on connecting visual features with
specific class text in downstream tasks, overlooking the latent relationships
between general and specialized knowledge. Our findings reveal that forcing
models to optimize inappropriate visual-text matches exacerbates forgetting of
VLMs. To tackle this issue, we propose DesCLIP, which leverages general
attribute (GA) descriptions to guide the understanding of specific class
objects, enabling VLMs to establish robust \textit\{vision-GA-class\} trilateral
associations rather than relying solely on \textit\{vision-class\} connections.
Specifically, we introduce a language assistant to generate concrete GA
description candidates via proper request prompts. Then, an anchor-based
embedding filter is designed to obtain highly relevant GA description
embeddings, which are leveraged as the paired text embeddings for
visual-textual instance matching, thereby tuning the visual encoder.
Correspondingly, the class text embeddings are gradually calibrated to align
with these shared GA description embeddings. Extensive experiments demonstrate
the advancements and efficacy of our proposed method, with comprehensive
empirical evaluations highlighting its superior performance compared to
existing pretrained and VLM-based continual learning methods.
