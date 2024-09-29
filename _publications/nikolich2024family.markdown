---
layout: publication
title: Vikhr\: The Family Of Open-source Instruction-tuned Large Language Models For Russian
authors: Nikolich Aleksandr, Korolev Konstantin, Shelmanov Artem, Kiselev Igor
conference: "Arxiv"
year: 2024
bibkey: nikolich2024family
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.13929"}
tags: ['Applications', 'Efficiency And Optimization', 'Fine Tuning', 'Language Modeling', 'Training Techniques']
---
There has been a surge in the development of various Large Language Models (LLMs). However text generation for languages other than English often faces significant challenges including poor generation quality and the reduced computational performance due to the disproportionate representation of tokens in models vocabulary. In this work we address these issues and introduce Vikhr a new state-of-the-art open-source instruction-tuned LLM designed specifically for the Russian language. Unlike previous efforts for Russian that utilize computationally inexpensive LoRA adapters on top of English-oriented models Vikhr features an adapted tokenizer vocabulary and undergoes the continued pre-training and instruction tuning of all weights. This approach not only enhances the models performance but also significantly improves its computational and contextual efficiency. The remarkable performance of Vikhr across various Russian-language benchmarks can also be attributed to our efforts in expanding instruction datasets and corpora for continued pre-training. Vikhr not only sets the new state of the art among open-source LLMs for Russian but even outperforms some proprietary closed-source models on certain benchmarks. The model weights instruction sets and code are publicly available
