---
layout: publication
title: 'Realm: Reference Resolution As Language Modeling'
authors: Joel Ruben Antony Moniz, Soundarya Krishnan, Melis Ozyildirim, Prathamesh Saraf, Halim Cagri Ates, Yuan Zhang, Hong Yu
conference: "Arxiv"
year: 2024
bibkey: moniz2024reference
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2403.20329'}
tags: ['Reinforcement Learning', 'GPT', 'Language Modeling', 'Model Architecture']
---
Reference resolution is an important problem, one that is essential to
understand and successfully handle context of different kinds. This context
includes both previous turns and context that pertains to non-conversational
entities, such as entities on the user's screen or those running in the
background. While LLMs have been shown to be extremely powerful for a variety
of tasks, their use in reference resolution, particularly for
non-conversational entities, remains underutilized. This paper demonstrates how
LLMs can be used to create an extremely effective system to resolve references
of various types, by showing how reference resolution can be converted into a
language modeling problem, despite involving forms of entities like those on
screen that are not traditionally conducive to being reduced to a text-only
modality. We demonstrate large improvements over an existing system with
similar functionality across different types of references, with our smallest
model obtaining absolute gains of over 5% for on-screen references. We also
benchmark against GPT-3.5 and GPT-4, with our smallest model achieving
performance comparable to that of GPT-4, and our larger models substantially
outperforming it.
