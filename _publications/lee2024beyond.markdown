---
layout: publication
title: 'Beyond Ontology In Dialogue State Tracking For Goal-oriented Chatbot'
authors: Sejin Lee, Dongha Kim, Min Song
conference: "IEEE International Conference on Knowledge Graph (ICKG) 2024 pp. 177-185"
year: 2024
bibkey: lee2024beyond
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.22767'}
tags: ['Reinforcement Learning', 'RAG', 'Prompting']
---
Goal-oriented chatbots are essential for automating user tasks, such as
booking flights or making restaurant reservations. A key component of these
systems is Dialogue State Tracking (DST), which interprets user intent and
maintains the dialogue state. However, existing DST methods often rely on fixed
ontologies and manually compiled slot values, limiting their adaptability to
open-domain dialogues. We propose a novel approach that leverages instruction
tuning and advanced prompt strategies to enhance DST performance, without
relying on any predefined ontologies. Our method enables Large Language Model
(LLM) to infer dialogue states through carefully designed prompts and includes
an anti-hallucination mechanism to ensure accurate tracking in diverse
conversation contexts. Additionally, we employ a Variational Graph Auto-Encoder
(VGAE) to model and predict subsequent user intent. Our approach achieved
state-of-the-art with a JGA of 42.57% outperforming existing ontology-less DST
models, and performed well in open-domain real-world conversations. This work
presents a significant advancement in creating more adaptive and accurate
goal-oriented chatbots.
