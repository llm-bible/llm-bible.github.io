---
layout: publication
title: 'Functional Abstraction Of Knowledge Recall In Large Language Models'
authors: Zijian Wang, Chang Xu
conference: "Arxiv"
year: 2025
bibkey: wang2025functional
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.14496'}
tags: ['Prompting', 'Transformer', 'Model Architecture', 'Pretraining Methods']
---
Pre-trained transformer large language models (LLMs) demonstrate strong
knowledge recall capabilities. This paper investigates the knowledge recall
mechanism in LLMs by abstracting it into a functional structure. We propose
that during knowledge recall, the model's hidden activation space implicitly
entails a function execution process where specific activation vectors align
with functional components (Input argument, Function body, and Return values).
Specifically, activation vectors of relation-related tokens define a mapping
function from subjects to objects, with subject-related token activations
serving as input arguments and object-related token activations as return
values. For experimental verification, we first design a patching-based
knowledge-scoring algorithm to identify knowledge-aware activation vectors as
independent functional components. Then, we conduct counter-knowledge testing
to examine the independent functional effects of each component on knowledge
recall outcomes. From this functional perspective, we improve the contextual
knowledge editing approach augmented by activation patching. By rewriting
incoherent activations in context, we enable improved short-term memory
retention for new knowledge prompting.
