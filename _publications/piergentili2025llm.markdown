---
layout: publication
title: 'An Llm-as-a-judge Approach For Scalable Gender-neutral Translation Evaluation'
authors: Andrea Piergentili, Beatrice Savoldi, Matteo Negri, Luisa Bentivogli
conference: "Arxiv"
year: 2025
bibkey: piergentili2025llm
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.11934'}
tags: ['Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Gender-neutral translation (GNT) aims to avoid expressing the gender of human
referents when the source text lacks explicit cues about the gender of those
referents. Evaluating GNT automatically is particularly challenging, with
current solutions being limited to monolingual classifiers. Such solutions are
not ideal because they do not factor in the source sentence and require
dedicated data and fine-tuning to scale to new languages. In this work, we
address such limitations by investigating the use of large language models
(LLMs) as evaluators of GNT. Specifically, we explore two prompting approaches:
one in which LLMs generate sentence-level assessments only, and another, akin
to a chain-of-thought approach, where they first produce detailed phrase-level
annotations before a sentence-level judgment. Through extensive experiments on
multiple languages with five models, both open and proprietary, we show that
LLMs can serve as evaluators of GNT. Moreover, we find that prompting for
phrase-level annotations before sentence-level assessments consistently
improves the accuracy of all models, providing a better and more scalable
alternative to current solutions.
