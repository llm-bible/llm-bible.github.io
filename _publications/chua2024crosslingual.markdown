---
layout: publication
title: Crosslingual Capabilities And Knowledge Barriers In Multilingual Large Language Models
authors: Chua Lynn, Ghazi Badih, Huang Yangsibo, Kamath Pritish, Kumar Ravi, Manurangsi Pasin, Sinha Amer, Xie Chulin, Zhang Chiyuan
conference: "Arxiv"
year: 2024
bibkey: chua2024crosslingual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.16135"}
  - {name: "Code", url: "https://github.com/google-research/crosslingual-knowledge-barriers"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Has Code', 'Pretraining Methods', 'Training Techniques']
---
Large language models (LLMs) are typically multilingual due to pretraining on diverse multilingual corpora. But can these models relate corresponding concepts across languages effectively being crosslingual This study evaluates six state-of-the-art LLMs on inherently crosslingual tasks. We observe that while these models show promising surface-level crosslingual abilities on machine translation and embedding space analyses they struggle with deeper crosslingual knowledge transfer revealing a crosslingual knowledge barrier in both general (MMLU benchmark) and domain-specific (Harry Potter quiz) contexts. We observe that simple inference-time mitigation methods offer only limited improvement. On the other hand we propose fine-tuning of LLMs on mixed-language data which effectively reduces these gaps even when using out-of-domain datasets like WikiText. Our findings suggest the need for explicit optimization to unlock the full crosslingual potential of LLMs. Our code is publicly available at https://github.com/google-research/crosslingual-knowledge-barriers.
