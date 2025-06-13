---
layout: publication
title: '\(\mu\)ke: Matryoshka Unstructured Knowledge Editing Of Large Language Models'
authors: Zian Su, Ziyang Huang, Kaiyuan Zhang, Xiangyu Zhang
conference: "Arxiv"
year: 2025
bibkey: su2025matryoshka
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.01196"}
tags: ['Responsible AI', 'GPT', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) have emerged as powerful knowledge bases yet are
limited by static training data, leading to issues such as hallucinations and
safety risks. Editing a model's internal knowledge through the locate-and-edit
paradigm has proven a cost-effective alternative to retraining, though current
unstructured approaches, especially window-based autoregressive methods, often
disrupt the causal dependency between early memory updates and later output
tokens. In this work, we first theoretically analyze these limitations and then
introduce Matryoshka Unstructured Knowledge Editing (\\(\mu\\)KE), a novel memory
update mechanism that preserves such dependencies via a Matryoshka-style
objective and adaptive loss coefficients. Empirical evaluations on two models
across four benchmarks demonstrate that \\(\mu\\)KE improves edit efficacy by up to
12.33% over state-of-the-art methods, and remain robust when applied to diverse
formatted edits, underscoring its potential for effective unstructured
knowledge editing in LLMs.
