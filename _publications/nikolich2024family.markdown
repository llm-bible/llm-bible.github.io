---
layout: publication
title: 'Vikhr: The Family Of Open-source Instruction-tuned Large Language Models For Russian'
authors: Aleksandr Nikolich, Konstantin Korolev, Sergei Bratchikov, Igor Kiselev, Artem Shelmanov
conference: "Arxiv"
year: 2024
bibkey: nikolich2024family
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.13929'}
tags: ['Language Modeling', 'Efficiency and Optimization', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Pre-Training']
---
There has been a surge in the development of various Large Language Models
(LLMs). However, text generation for languages other than English often faces
significant challenges, including poor generation quality and reduced
computational performance due to the disproportionate representation of tokens
in the model's vocabulary. In this work, we address these issues by developing
a pipeline for the adaptation of English-oriented pre-trained models to other
languages and constructing efficient bilingual LLMs. Using this pipeline, we
construct Vikhr, a series of bilingual open-source instruction-following LLMs
designed specifically for the Russian language. ``Vikhr'' refers to the name of
the Mistral LLM series and means a ``strong gust of wind.'' Unlike previous
Russian-language models that typically rely on LoRA adapters on top of
English-oriented models, sacrificing performance for lower training costs,
Vikhr features an adapted tokenizer vocabulary and undergoes the continued
pre-training and instruction tuning of all weights. This not only enhances the
model's performance but also significantly improves its computational and
contextual efficiency. We also expanded the instruction datasets and corpora
for continued pre-training. The model weights, instruction sets, and code are
publicly available.
