---
layout: publication
title: 'Visually-augmented Language Modeling'
authors: Weizhi Wang, Li Dong, Hao Cheng, Haoyu Song, Xiaodong Liu, Xifeng Yan, Jianfeng Gao, Furu Wei
conference: "Arxiv"
year: 2022
bibkey: wang2022visually
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2205.10178'}
  - {name: "Code", url: 'https://github.com/Victorwz/VaLM'}
tags: ['Has Code', 'Language Modeling', 'Training Techniques', 'Tools', 'Merging', 'Multimodal Models', 'Pre-Training']
---
Human language is grounded on multimodal knowledge including visual knowledge
like colors, sizes, and shapes. However, current large-scale pre-trained
language models rely on text-only self-supervised training with massive text
data, which precludes them from utilizing relevant visual information when
necessary. To address this, we propose a novel pre-training framework, named
VaLM, to Visually-augment text tokens with retrieved relevant images for
Language Modeling. Specifically, VaLM builds on a novel latent text-image
alignment method via an image retrieval module to fetch corresponding images
given a textual context. With the visually-augmented context, VaLM uses a
visual knowledge fusion layer to enable multimodal grounded language modeling
by attending to both text context and visual knowledge in images. We evaluate
VaLM on various visual knowledge-intensive commonsense reasoning tasks, which
require visual information to excel. The experimental results illustrate that
VaLM outperforms all strong language-only and vision-language baselines with
substantial gains in reasoning object commonsense including color, size, and
shape. Our code is available at https://github.com/Victorwz/VaLM.
