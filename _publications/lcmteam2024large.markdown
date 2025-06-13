---
layout: publication
title: 'Large Concept Models: Language Modeling In A Sentence Representation Space'
authors: Lcm Team, Loïc Barrault, Paul-ambroise Duquenne, Maha Elbayad, Artyom Kozhevnikov, Belen Alastruey, Pierre Andrews, Mariano Coria, Guillaume Couairon, Marta R. Costa-jussà, David Dale, Hady Elsahar, Kevin Heffernan, João Maria Janeiro, Tuan Tran, Christophe Ropers, Eduardo Sánchez, Robin San Roman, Alexandre Mourachko, Safiyyah Saleem, Holger Schwenk
conference: "Arxiv"
year: 2024
bibkey: lcmteam2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.08821"}
tags: ['Fine-Tuning', 'GPT', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Language Modeling', 'Merging', 'Training Techniques', 'Pretraining Methods']
---
LLMs have revolutionized the field of artificial intelligence and have
emerged as the de-facto tool for many tasks. The current established technology
of LLMs is to process input and generate output at the token level. This is in
sharp contrast to humans who operate at multiple levels of abstraction, well
beyond single words, to analyze information and to generate creative content.
In this paper, we present an attempt at an architecture which operates on an
explicit higher-level semantic representation, which we name a concept.
Concepts are language- and modality-agnostic and represent a higher level idea
or action in a flow. Hence, we build a "Large Concept Model". In this study, as
proof of feasibility, we assume that a concept corresponds to a sentence, and
use an existing sentence embedding space, SONAR, which supports up to 200
languages in both text and speech modalities.
  The Large Concept Model is trained to perform autoregressive sentence
prediction in an embedding space. We explore multiple approaches, namely MSE
regression, variants of diffusion-based generation, and models operating in a
quantized SONAR space. These explorations are performed using 1.6B parameter
models and training data in the order of 1.3T tokens. We then scale one
architecture to a model size of 7B parameters and training data of about 2.7T
tokens. We perform an experimental evaluation on several generative tasks,
namely summarization and a new task of summary expansion. Finally, we show that
our model exhibits impressive zero-shot generalization performance to many
languages, outperforming existing LLMs of the same size. The training code of
our models is freely available.
