---
layout: publication
title: 'Do Llms Dream Of Ontologies?'
authors: Bombieri Marco, Fiorini Paolo, Ponzetto Simone Paolo, Rospocher Marco
conference: "Arxiv"
year: 2024
bibkey: bombieri2024do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.14931"}
tags: ['Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have recently revolutionized automated text
understanding and generation. The performance of these models relies on the
high number of parameters of the underlying neural architectures, which allows
LLMs to memorize part of the vast quantity of data seen during the training.
This paper investigates whether and to what extent general-purpose pre-trained
LLMs have memorized information from known ontologies. Our results show that
LLMs partially know ontologies: they can, and do indeed, memorize concepts from
ontologies mentioned in the text, but the level of memorization of their
concepts seems to vary proportionally to their popularity on the Web, the
primary source of their training material. We additionally propose new metrics
to estimate the degree of memorization of ontological information in LLMs by
measuring the consistency of the output produced across different prompt
repetitions, query languages, and degrees of determinism.
