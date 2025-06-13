---
layout: publication
title: 'How Many Languages Make Good Multilingual Instruction Tuning? A Case Study On BLOOM'
authors: Shaoxiong Ji, Pinzhen Chen
conference: "Arxiv"
year: 2024
bibkey: ji2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04850"}
tags: ['Fine-Tuning', 'RAG', 'Training Techniques', 'Pretraining Methods']
---
Instruction tuning a large language model with multiple languages can prepare
it for multilingual downstream tasks. Nonetheless, it is yet to be determined
whether having a handful of languages is sufficient, or whether the benefits
increase with the inclusion of more. By fine-tuning large multilingual models
on 1 to 52 languages, we present a case study on BLOOM to understand three
pertinent factors affecting performance: the number of languages, language
exposure, and similarity between training and test languages. Overall we found
that 1) expanding language coverage in multilingual instruction tuning proves
to be beneficial; 2) accuracy often significantly boots if the test language
appears in the instruction mixture; 3) languages' genetic features correlate
with cross-lingual transfer more than merely the number of language but
different languages benefit to various degrees.
