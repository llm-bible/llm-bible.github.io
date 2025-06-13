---
layout: publication
title: 'Can Large Language Models Learn Formal Logic? A Data-driven Training And Evaluation Framework'
authors: Yuan Xia, Akanksha Atrey, Fadoua Khmaissia, Kedar S. Namjoshi
conference: "Arxiv"
year: 2025
bibkey: xia2025can
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.20213'}
tags: ['ACL', 'Training Techniques', 'Tools', 'Reinforcement Learning', 'TACL']
---
This paper investigates the logical reasoning capabilities of large language
models (LLMs). For a precisely defined yet tractable formulation, we choose the
conceptually simple but technically complex task of constructing proofs in
Boolean logic. A trained LLM receives as input a set of assumptions and a goal,
and produces as output a proof that formally derives the goal from the
assumptions. Incorrect proofs are caught by an automated proof checker. A
critical obstacle for training is the scarcity of real-world proofs. We propose
an efficient, randomized procedure for synthesizing valid proofs and introduce
Template Transformation, a data augmentation technique that enhances the
model's ability to handle complex logical expressions. The central evaluation
question is whether an LLM has indeed learned to reason. We propose tests to
measure the reasoning ability of a black-box LLM. By these measures,
experiments demonstrate strong reasoning capabilities for assertions with short
proofs, which decline with proof complexity. Notably, template transformation
improves accuracy even for smaller models, suggesting its effectiveness across
model scales.
