---
layout: publication
title: 'Molar: Multimodal Llms With Collaborative Filtering Alignment For Enhanced Sequential Recommendation'
authors: Yucong Luo, Qitao Qin, Hao Zhang, Mingyue Cheng, Ruiran Yan, Kefan Wang, Jie Ouyang
conference: "Arxiv"
year: 2024
bibkey: luo2024multimodal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.18176'}
  - {name: "Code", url: 'https://anonymous.4open.science/r/Molar-8B06/'}
tags: ['Has Code', 'Multimodal Models', 'Tools']
---
Sequential recommendation (SR) systems have evolved significantly over the
past decade, transitioning from traditional collaborative filtering to deep
learning approaches and, more recently, to large language models (LLMs). While
the adoption of LLMs has driven substantial advancements, these models
inherently lack collaborative filtering information, relying primarily on
textual content data neglecting other modalities and thus failing to achieve
optimal recommendation performance. To address this limitation, we propose
Molar, a Multimodal large language sequential recommendation framework that
integrates multiple content modalities with ID information to capture
collaborative signals effectively. Molar employs an MLLM to generate unified
item representations from both textual and non-textual data, facilitating
comprehensive multimodal modeling and enriching item embeddings. Additionally,
it incorporates collaborative filtering signals through a post-alignment
mechanism, which aligns user representations from content-based and ID-based
models, ensuring precise personalization and robust performance. By seamlessly
combining multimodal content with collaborative filtering insights, Molar
captures both user interests and contextual semantics, leading to superior
recommendation accuracy. Extensive experiments validate that Molar
significantly outperforms traditional and LLM-based baselines, highlighting its
strength in utilizing multimodal data and collaborative signals for sequential
recommendation tasks. The source code is available at
https://anonymous.4open.science/r/Molar-8B06/.
