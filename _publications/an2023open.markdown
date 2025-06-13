---
layout: publication
title: 'Openleaf: Open-domain Interleaved Image-text Generation And Evaluation'
authors: Jie An, Zhengyuan Yang, Linjie Li, Jianfeng Wang, Kevin Lin, Zicheng Liu, Lijuan Wang, Jiebo Luo
conference: "Arxiv"
year: 2023
bibkey: an2023open
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.07749"}
tags: ['Multimodal Models', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'Prompting', 'Applications']
---
This work investigates a challenging task named open-domain interleaved
image-text generation, which generates interleaved texts and images following
an input query. We propose a new interleaved generation framework based on
prompting large-language models (LLMs) and pre-trained text-to-image (T2I)
models, namely OpenLEAF. In OpenLEAF, the LLM generates textual descriptions,
coordinates T2I models, creates visual prompts for generating images, and
incorporates global contexts into the T2I models. This global context improves
the entity and style consistencies of images in the interleaved generation. For
model assessment, we first propose to use large multi-modal models (LMMs) to
evaluate the entity and style consistencies of open-domain interleaved
image-text sequences. According to the LMM evaluation on our constructed
evaluation set, the proposed interleaved generation framework can generate
high-quality image-text content for various domains and applications, such as
how-to question answering, storytelling, graphical story rewriting, and
webpage/poster generation tasks. Moreover, we validate the effectiveness of the
proposed LMM evaluation technique with human assessment. We hope our proposed
framework, benchmark, and LMM evaluation could help establish the intriguing
interleaved image-text generation task.
