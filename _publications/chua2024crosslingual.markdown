---
layout: publication
title: 'Crosslingual Capabilities And Knowledge Barriers In Multilingual Large Language Models'
authors: Lynn Chua, Badih Ghazi, Yangsibo Huang, Pritish Kamath, Ravi Kumar, Pasin Manurangsi, Amer Sinha, Chulin Xie, Chiyuan Zhang
conference: "Arxiv"
year: 2024
bibkey: chua2024crosslingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16135"}
  - {name: "Code", url: "https://github.com/google-research/crosslingual-knowledge-barriers"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Pretraining Methods', 'Fine-Tuning', 'Has Code']
---
Large language models (LLMs) are typically multilingual due to pretraining on
diverse multilingual corpora. But can these models relate corresponding
concepts across languages, i.e., be crosslingual? This study evaluates
state-of-the-art LLMs on inherently crosslingual tasks. We observe that while
these models show promising surface-level crosslingual abilities on machine
translation and embedding space analyses, they struggle with deeper
crosslingual knowledge transfer, revealing a crosslingual knowledge barrier in
both general (MMLU benchmark) and domain-specific (Harry Potter quiz and TOFU
benchmark) contexts. Since simple inference-time mitigation methods offer only
limited improvement, we propose fine-tuning of LLMs on mixed-language data,
which effectively reduces these gaps, even when using out-of-domain datasets
like WikiText. Our findings suggest the need for explicit optimization to
unlock the full crosslingual potential of LLMs. Our code is publicly available
at https://github.com/google-research/crosslingual-knowledge-barriers.
