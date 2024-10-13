---
layout: publication
title: 'Augmented Large Language Models With Parametric Knowledge Guiding'
authors: Luo Ziyang, Xu Can, Zhao Pu, Geng Xiubo, Tao Chongyang, Ma Jing, Lin Qingwei, Jiang Daxin
conference: "Arxiv"
year: 2023
bibkey: luo2023augmented
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.04757"}
tags: ['Ethics And Bias', 'Fine Tuning', 'Multimodal Models', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) have significantly advanced natural language
processing (NLP) with their impressive language understanding and generation
capabilities. However, their performance may be suboptimal for domain-specific
tasks that require specialized knowledge due to limited exposure to the related
data. Additionally, the lack of transparency of most state-of-the-art (SOTA)
LLMs, which can only be accessed via APIs, impedes further fine-tuning with
domain custom data. Moreover, providing private data to the LLMs' owner leads
to data privacy problems. To address these challenges, we propose the novel
Parametric Knowledge Guiding (PKG) framework, which equips LLMs with a
knowledge-guiding module to access relevant knowledge without altering the
LLMs' parameters. Our PKG is based on open-source "white-box" language models,
allowing offline memory of any knowledge that LLMs require. We demonstrate that
our PKG framework can enhance the performance of "black-box" LLMs on a range of
domain knowledge-intensive tasks that require factual (+7.9%), tabular
(+11.9%), medical (+3.0%), and multimodal (+8.1%) knowledge.
