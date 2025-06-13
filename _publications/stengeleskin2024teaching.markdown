---
layout: publication
title: 'Teaching Models To Balance Resisting And Accepting Persuasion'
authors: Elias Stengel-eskin, Peter Hase, Mohit Bansal
conference: "Arxiv"
year: 2024
bibkey: stengeleskin2024teaching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14596"}
tags: ['Agentic', 'Security', 'Training Techniques', 'Efficiency and Optimization', 'Reinforcement Learning', 'RAG']
---
Large language models (LLMs) are susceptible to persuasion, which can pose
risks when models are faced with an adversarial interlocutor. We take a first
step towards defending models against persuasion while also arguing that
defense against adversarial (i.e. negative) persuasion is only half of the
equation: models should also be able to accept beneficial (i.e. positive)
persuasion to improve their answers. We show that optimizing models for only
one side results in poor performance on the other. In order to balance positive
and negative persuasion, we introduce Persuasion-Training (or PBT), which
leverages multi-agent recursive dialogue trees to create data and trains models
via preference optimization to accept persuasion when appropriate. PBT allows
us to use data generated from dialogues between smaller 7-8B models for
training much larger 70B models. Moreover, PBT consistently improves resistance
to misinformation and resilience to being challenged while also resulting in
the best overall performance on holistic data containing both positive and
negative persuasion. Crucially, we show that PBT models are better teammates in
multi-agent debates across two domains (trivia and commonsense QA). We find
that without PBT, pairs of stronger and weaker models have unstable
performance, with the order in which the models present their answers
determining whether the team obtains the stronger or weaker model's
performance. PBT leads to better and more stable results and less order
dependence, with the stronger model consistently pulling the weaker one up.
