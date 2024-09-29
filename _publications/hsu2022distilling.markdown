---
layout: publication
title: XDBERT: Distilling Visual Information To BERT From Cross-modal Systems To Improve Language Understanding
authors: Hsu Chan-jan, Lee Hung-yi, Tsao Yu
conference: "Arxiv"
year: 2022
bibkey: hsu2022distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.07316"}
tags: ['Applications', 'BERT', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Security', 'Tools', 'Training Techniques', 'Transformer']
---
Transformer-based models are widely used in natural language understanding (NLU) tasks and multimodal transformers have been effective in visual-language tasks. This study explores distilling visual information from pretrained multimodal transformers to pretrained language encoders. Our framework is inspired by cross-modal encoders success in visual-language tasks while we alter the learning objective to cater to the language-heavy characteristics of NLU. After training with a small number of extra adapting steps and finetuned the proposed XDBERT (cross-modal distilled BERT) outperforms pretrained-BERT in general language understanding evaluation (GLUE) situations with adversarial generations (SWAG) benchmarks and readability benchmarks. We analyze the performance of XDBERT on GLUE to show that the improvement is likely visually grounded.
