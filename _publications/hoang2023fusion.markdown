---
layout: publication
title: 'On-the-fly Fusion Of Large Language Models And Machine Translation'
authors: Hieu Hoang, Huda Khayrallah, Marcin Junczys-dowmunt
conference: "Arxiv"
year: 2023
bibkey: hoang2023fusion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.08306"}
tags: ['Prompting', 'Applications', 'Merging']
---
We propose the on-the-fly ensembling of a machine translation model with an
LLM, prompted on the same task and input. We perform experiments on 4 language
pairs (both directions) with varying data amounts. We find that a slightly
weaker-at-translation LLM can improve translations of a NMT model, and
ensembling with an LLM can produce better translations than ensembling two
stronger MT models. We combine our method with various techniques from LLM
prompting, such as in context learning and translation context.
