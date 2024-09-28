---
layout: publication
title: Guiding In-Context Learning of LLMs through Quality Estimation for Machine Translation
authors: Sharami Javad Pourmostafa Roshan, Shterionov Dimitar, Spronck Pieter
conference: "Arxiv"
year: 2024
bibkey: sharami2024guiding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.07970"}
tags: ['ARXIV', 'Pretraining Methods']
---
The quality of output from large language models (LLMs) particularly in machine translation (MT) is closely tied to the quality of in-context examples (ICEs) provided along with the query i.e. the text to translate. The effectiveness of these ICEs is influenced by various factors such as the domain of the source text the order in which the ICEs are presented the number of these examples and the prompt templates used. Naturally selecting the most impactful ICEs depends on understanding how these affect the resulting translation quality which ultimately relies on translation references or human judgment. This paper presents a novel methodology for in-context learning (ICL) that relies on a search algorithm guided by domain-specific quality estimation (QE). Leveraging the XGLM model our methodology estimates the resulting translation quality without the need for translation references selecting effective ICEs for MT to maximize translation quality. Our results demonstrate significant improvements over existing ICL methods and higher translation performance compared to fine-tuning a pre-trained language model (PLM) specifically mBART-50.
