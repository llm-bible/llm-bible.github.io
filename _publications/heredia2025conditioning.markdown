---
layout: publication
title: 'Conditioning Llms To Generate Code-switched Text'
authors: Maite Heredia, Gorka Labaka, Jeremy Barnes, Aitor Soroa
conference: "Arxiv"
year: 2025
bibkey: heredia2025conditioning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12924"}
tags: ['Training Techniques', 'Reinforcement Learning']
---
Code-switching (CS) is still a critical challenge in Natural Language Processing (NLP). Current Large Language Models (LLMs) struggle to interpret and generate code-switched text, primarily due to the scarcity of large-scale CS datasets for training. This paper presents a novel methodology to generate CS data using LLMs, and test it on the English-Spanish language pair. We propose back-translating natural CS sentences into monolingual English, and using the resulting parallel corpus to fine-tune LLMs to turn monolingual sentences into CS. Unlike previous approaches to CS generation, our methodology uses natural CS data as a starting point, allowing models to learn its natural distribution beyond grammatical patterns. We thoroughly analyse the models' performance through a study on human preferences, a qualitative error analysis and an evaluation with popular automatic metrics. Results show that our methodology generates fluent code-switched text, expanding research opportunities in CS communication, and that traditional metrics do not correlate with human judgement when assessing the quality of the generated CS data. We release our code and generated dataset under a CC-BY-NC-SA license.
