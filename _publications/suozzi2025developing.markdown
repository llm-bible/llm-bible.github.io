---
layout: publication
title: 'BAMBI: Developing Baby Language Models For Italian'
authors: Alice Suozzi, Luca Capone, Gianluca E. Lebani, Alessandro Lenci
conference: "Arxiv"
year: 2025
bibkey: suozzi2025developing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.09481'}
tags: ['Reinforcement Learning', 'Multimodal Models', 'Training Techniques', 'Tools']
---
This paper presents BAMBI (BAby language Models Boostrapped for Italian), a
series of Baby Language Models (BabyLMs) trained on data that mimic the
linguistic input received by a five-year-old Italian-speaking child. The BAMBI
models are tested using a benchmark specifically designed to evaluate language
models, which takes into account the amount of training input the models
received. The BAMBI models are compared against a large language model (LLM)
and a multimodal language model (VLM) to study the contribution of
extralinguistic information for language acquisition. The results of our
evaluation align with the existing literature on English language models,
confirming that while reduced training data support the development of
relatively robust syntactic competence, they are insufficient for fostering
semantic understanding. However, the gap between the training resources (data
and computation) of the BAMBI models and the LLMs is not fully reflected in
their performance: despite LLMs' massive training, their performance is not
much better than that of BAMBI models. This suggests that strategies beyond
scaling training resources, such as data curation, inclusion of multimodal
input, and other training strategies such as curriculum learning, could play a
crucial role in shaping model performance.
