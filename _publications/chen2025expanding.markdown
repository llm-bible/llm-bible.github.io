---
layout: publication
title: 'Expanding Before Inferring: Enhancing Factuality In Large Language Models Through Premature Layers Interpolation'
authors: Dingwei Chen, Ziqiang Liu, Feiteng Fang, Chak Tou Leong, Shiwen Ni, Ahmadreza Argha, Hamid Alinejad-rokny, Min Yang, Chengming Li
conference: "Arxiv"
year: 2025
bibkey: chen2025expanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.02973'}
tags: ['Training Techniques', 'Merging', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) demonstrate remarkable capabilities in text understanding and generation. However, their tendency to produce factually inconsistent outputs, commonly referred to as ''hallucinations'', remains a critical challenge. Existing approaches, such as retrieval-based and inference-time correction methods, primarily address this issue at the input or output level, often overlooking the intrinsic information refinement process and the role of premature layers. Meanwhile, alignment- and fine-tuning-based methods are resource-intensive. In this paper, we propose PLI (Premature Layers Interpolation), a novel, training-free, and plug-and-play intervention designed to enhance factuality. PLI mitigates hallucinations by inserting premature layers formed through mathematical interpolation with adjacent layers. Inspired by stable diffusion and sampling steps, PLI extends the depth of information processing and transmission in LLMs, improving factual coherence. Experiments on four publicly available datasets demonstrate that PLI effectively reduces hallucinations while outperforming existing baselines in most cases. Further analysis suggests that the success of layer interpolation is closely linked to LLMs' internal mechanisms. To promote reproducibility, we will release our code and data upon acceptance.
