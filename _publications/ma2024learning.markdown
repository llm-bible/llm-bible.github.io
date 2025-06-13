---
layout: publication
title: 'Clawmachine: Learning To Fetch Visual Tokens For Referential Comprehension'
authors: Tianren Ma, Lingxi Xie, Yunjie Tian, Boyu Yang, Qixiang Ye
conference: "Arxiv"
year: 2024
bibkey: ma2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11327"}
tags: ['Pre-Training', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models', 'Prompting']
---
Aligning vision and language concepts at a finer level remains an essential
topic of multimodal large language models (MLLMs), particularly for tasks such
as referring and grounding. Existing methods, such as proxy encoding and
geometry encoding, incorporate additional syntax to encode spatial information,
imposing extra burdens when communicating between language and vision modules.
In this study, we propose ClawMachine, offering a new methodology that
explicitly notates each entity using token collectives groups of visual tokens
that collaboratively represent higher level semantics. A hybrid perception
mechanism is also explored to perceive and understand scenes from both discrete
and continuous spaces. Our method unifies the prompt and answer of visual
referential tasks without using additional syntax. By leveraging a joint
vision-language vocabulary, ClawMachine further integrates referring and
grounding in an auto-regressive manner, demonstrating great potential with
scaled-up pre-training data. Experiments show that ClawMachine achieves
superior performance on scene-level and referential understanding tasks with
higher efficiency. It also exhibits the potential to integrate multi-source
information for complex visual reasoning, which is beyond the capability of
many MLLMs. Our code is available at github.com/martian422/ClawMachine.
