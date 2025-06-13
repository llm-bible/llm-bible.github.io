---
layout: publication
title: 'To Each (textual Sequence) Its Own: Improving Memorized-data Unlearning In Large Language Models'
authors: George-octavian Barbulescu, Peter Triantafillou
conference: "Arxiv"
year: 2024
bibkey: barbulescu2024each
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.03097'}
tags: ['Language Modeling', 'Security', 'Applications', 'Training Techniques', 'Reinforcement Learning']
---
LLMs have been found to memorize training textual sequences and regurgitate
verbatim said sequences during text generation time. This fact is known to be
the cause of privacy and related (e.g., copyright) problems. Unlearning in LLMs
then takes the form of devising new algorithms that will properly deal with
these side-effects of memorized data, while not hurting the model's utility. We
offer a fresh perspective towards this goal, namely, that each textual sequence
to be forgotten should be treated differently when being unlearned based on its
degree of memorization within the LLM. We contribute a new metric for measuring
unlearning quality, an adversarial attack showing that SOTA algorithms lacking
this perspective fail for privacy, and two new unlearning methods based on
Gradient Ascent and Task Arithmetic, respectively. A comprehensive performance
evaluation across an extensive suite of NLP tasks then mapped the solution
space, identifying the best solutions under different scales in model
capacities and forget set sizes and quantified the gains of the new approaches.
