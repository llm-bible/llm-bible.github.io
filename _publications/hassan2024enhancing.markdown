---
layout: publication
title: 'Enhancing Naturalness In Llm-generated Utterances Through Disfluency Insertion'
authors: Syed Zohaib Hassan, Pierre Lison, Pål Halvorsen
conference: "Arxiv"
year: 2024
bibkey: hassan2024enhancing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.12710'}
tags: ['Agentic', 'Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Disfluencies are a natural feature of spontaneous human speech but are
typically absent from the outputs of Large Language Models (LLMs). This absence
can diminish the perceived naturalness of synthesized speech, which is an
important criteria when building conversational agents that aim to mimick human
behaviours. We show how the insertion of disfluencies can alleviate this
shortcoming. The proposed approach involves (1) fine-tuning an LLM with
Low-Rank Adaptation (LoRA) to incorporate various types of disfluencies into
LLM-generated utterances and (2) synthesizing those utterances using a
text-to-speech model that supports the generation of speech phenomena such as
disfluencies. We evaluated the quality of the generated speech across two
metrics: intelligibility and perceived spontaneity. We demonstrate through a
user study that the insertion of disfluencies significantly increase the
perceived spontaneity of the generated speech. This increase came, however,
along with a slight reduction in intelligibility.
