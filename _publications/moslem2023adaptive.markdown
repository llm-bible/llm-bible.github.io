---
layout: publication
title: Adaptive Machine Translation With Large Language Models
authors: Moslem Yasmin, Haque Rejwanul, Kelleher John D., Way Andy
conference: "Arxiv"
year: 2023
bibkey: moslem2023adaptive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2301.13294"}
tags: ['Applications', 'Fine Tuning', 'Language Modeling', 'Prompting', 'Reinforcement Learning']
---
Consistency is a key requirement of high45;quality translation. It is especially important to adhere to pre45;approved terminology and adapt to corrected translations in domain45;specific projects. Machine translation (MT) has achieved significant progress in the area of domain adaptation. However real45;time adaptation remains challenging. Large45;scale language models (LLMs) have recently shown interesting capabilities of in45;context learning where they learn to replicate certain input45;output text generation patterns without further fine45;tuning. By feeding an LLM at inference time with a prompt that consists of a list of translation pairs it can then simulate the domain and style characteristics. This work aims to investigate how we can utilize in45;context learning to improve real45;time adaptive MT. Our extensive experiments show promising results at translation time. For example LLMs can adapt to a set of in45;domain sentence pairs and/or terminology while translating a new sentence. We observe that the translation quality with few45;shot in45;context learning can surpass that of strong encoder45;decoder MT systems especially for high45;resource languages. Moreover we investigate whether we can combine MT from strong encoder45;decoder models with fuzzy matches which can further improve translation quality especially for less supported languages. We conduct our experiments across five diverse language pairs namely English45;to45;Arabic (EN45;AR) English45;to45;Chinese (EN45;ZH) English45;to45;French (EN45;FR) English45;to45;Kinyarwanda (EN45;RW) and English45;to45;Spanish (EN45;ES).
