---
layout: publication
title: Teaching the Pre-trained Model to Generate Simple Texts for Text Simplification
authors: Sun Renliang, Xu Wei, Wan Xiaojun
conference: "Arxiv"
year: 2023
bibkey: sun2023teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.12463"}
tags: ['Pretraining Methods', 'Training Techniques']
---
Randomly masking text spans in ordinary texts in the pre-training stage hardly allows models to acquire the ability to generate simple texts. It can hurt the performance of pre-trained models on text simplification tasks. In this paper we propose a new continued pre-training strategy to teach the pre-trained model to generate simple texts. We continue pre-training BART a representative model to obtain SimpleBART. It consistently and significantly improves the results on lexical simplification sentence simplification and document-level simplification tasks over BART. At the end we compare SimpleBART with several representative large language models (LLMs).
