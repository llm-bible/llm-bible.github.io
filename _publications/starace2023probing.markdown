---
layout: publication
title: 'Probing Llms For Joint Encoding Of Linguistic Categories'
authors: Starace Giulio, Papakostas Konstantinos, Choenni Rochelle, Panagiotopoulos Apostolos, Rosati Matteo, Leidinger Alina, Shutova Ekaterina
conference: "Arxiv"
year: 2023
bibkey: starace2023probing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.18696"}
tags: ['Interpretability And Explainability', 'Pretraining Methods', 'Tools', 'Training Techniques']
---
Large Language Models (LLMs) exhibit impressive performance on a range of NLP
tasks, due to the general-purpose linguistic knowledge acquired during
pretraining. Existing model interpretability research (Tenney et al., 2019)
suggests that a linguistic hierarchy emerges in the LLM layers, with lower
layers better suited to solving syntactic tasks and higher layers employed for
semantic processing. Yet, little is known about how encodings of different
linguistic phenomena interact within the models and to what extent processing
of linguistically-related categories relies on the same, shared model
representations. In this paper, we propose a framework for testing the joint
encoding of linguistic categories in LLMs. Focusing on syntax, we find evidence
of joint encoding both at the same (related part-of-speech (POS) classes) and
different (POS classes and related syntactic dependency relations) levels of
linguistic hierarchy. Our cross-lingual experiments show that the same patterns
hold across languages in multilingual LLMs.
