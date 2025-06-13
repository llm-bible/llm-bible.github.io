---
layout: publication
title: 'Delusions Of Large Language Models'
authors: Hongshen Xu, Zixv Yang, Zichen Zhu, Kunyao Lan, Zihan Wang, Mengyue Wu, Ziwei Ji, Lu Chen, Pascale Fung, Kai Yu
conference: "Arxiv"
year: 2025
bibkey: xu2025delusions
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.06709'}
tags: ['Reinforcement Learning', 'Agentic', 'Applications', 'Training Techniques']
---
Large Language Models often generate factually incorrect but plausible
outputs, known as hallucinations. We identify a more insidious phenomenon, LLM
delusion, defined as high belief hallucinations, incorrect outputs with
abnormally high confidence, making them harder to detect and mitigate. Unlike
ordinary hallucinations, delusions persist with low uncertainty, posing
significant challenges to model reliability. Through empirical analysis across
different model families and sizes on several Question Answering tasks, we show
that delusions are prevalent and distinct from hallucinations. LLMs exhibit
lower honesty with delusions, which are harder to override via finetuning or
self reflection. We link delusion formation with training dynamics and dataset
noise and explore mitigation strategies such as retrieval augmented generation
and multi agent debating to mitigate delusions. By systematically investigating
the nature, prevalence, and mitigation of LLM delusions, our study provides
insights into the underlying causes of this phenomenon and outlines future
directions for improving model reliability.
