---
layout: publication
title: "Novicode: Generating Programs From Natural Language Utterances By Novices"
authors: Mordechai Asaf Achi, Goldberg Yoav, Tsarfaty Reut
conference: "Arxiv"
year: 2024
bibkey: mordechai2024generating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.10626"}
tags: ['Applications', 'Tools']
---
Current Text-to-Code models demonstrate impressive capabilities in generating executable code from natural language snippets. However current studies focus on technical instructions and programmer-oriented language and it is an open question whether these models can effectively translate natural language descriptions given by non-technical users and express complex goals to an executable program that contains an intricate flow - composed of API access and control structures as loops conditions and sequences. To unlock the challenge of generating a complete program from a plain non-technical description we present NoviCode a novel NL Programming task which takes as input an API and a natural language description by a novice non-programmer and provides an executable program as output. To assess the efficacy of models on this task we provide a novel benchmark accompanied by test suites wherein the generated program code is assessed not according to their form but according to their functional execution. Our experiments show that first NoviCode is indeed a challenging task in the code synthesis domain and that generating complex code from non-technical instructions goes beyond the current Text-to-Code paradigm. Second we show that a novel approach wherein we align the NL utterances with the compositional hierarchical structure of the code greatly enhances the performance of LLMs on this task compared with the end-to-end Text-to-Code counterparts.
