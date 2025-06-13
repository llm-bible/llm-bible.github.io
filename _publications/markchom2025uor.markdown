---
layout: publication
title: 'Uor-ncl At Semeval-2025 Task 1: Using Generative Llms And CLIP Models For Multilingual Multimodal Idiomaticity Representation'
authors: Thanet Markchom, Tong Wu, Liting Huang, Huizhi Liang
conference: "Arxiv"
year: 2025
bibkey: markchom2025uor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.20984"}
  - {name: "Code", url: "https://github.com/tongwu17/SemEval-2025-Task1-UoR-NCL"}
tags: ['Fine-Tuning', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Multimodal Models']
---
SemEval-2025 Task 1 focuses on ranking images based on their alignment with a
given nominal compound that may carry idiomatic meaning in both English and
Brazilian Portuguese. To address this challenge, this work uses generative
large language models (LLMs) and multilingual CLIP models to enhance idiomatic
compound representations. LLMs generate idiomatic meanings for potentially
idiomatic compounds, enriching their semantic interpretation. These meanings
are then encoded using multilingual CLIP models, serving as representations for
image ranking. Contrastive learning and data augmentation techniques are
applied to fine-tune these embeddings for improved performance. Experimental
results show that multimodal representations extracted through this method
outperformed those based solely on the original nominal compounds. The
fine-tuning approach shows promising outcomes but is less effective than using
embeddings without fine-tuning. The source code used in this paper is available
at https://github.com/tongwu17/SemEval-2025-Task1-UoR-NCL.
