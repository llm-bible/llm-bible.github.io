---
layout: publication
title: 'Controllable And Diverse Data Augmentation With Large Language Model For Low-resource Open-domain Dialogue Generation'
authors: Zhenhua Liu, Tong Zhu, Jianxiang Xiang, Wenliang Chen
conference: "Arxiv"
year: 2024
bibkey: liu2024controllable
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.00361'}
tags: ['Training Techniques']
---
Data augmentation (DA) is crucial to mitigate model training instability and
over-fitting problems in low-resource open-domain dialogue generation. However,
traditional DA methods often neglect semantic data diversity, restricting the
overall quality. Recently, large language models (LLM) have been used for DA to
generate diversified dialogues. However, they have limited controllability and
tend to generate dialogues with a distribution shift compared to the seed
dialogues. To maximize the augmentation diversity and address the
controllability problem, we propose \textbf\{S\}ummary-based \textbf\{D\}ialogue
\textbf\{A\}ugmentation with LLM (SDA). Our approach enhances the controllability
of LLM by using dialogue summaries as a planning tool. Based on summaries, SDA
can generate high-quality and diverse dialogue data even with a small seed
dataset. To evaluate the efficacy of data augmentation methods for open-domain
dialogue, we designed a clustering-based metric to characterize the semantic
diversity of the augmented dialogue data. The experimental results show that
SDA can augment high-quality and semantically diverse dialogues given a small
seed dataset and an LLM, and the augmented data can boost the performance of
open-domain dialogue models.
