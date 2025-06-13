---
layout: publication
title: 'Llms As Repositories Of Factual Knowledge: Limitations And Solutions'
authors: Seyed Mahed Mousavi, Simone Alghisi, Giuseppe Riccardi
conference: "Arxiv"
year: 2025
bibkey: mousavi2025llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.12774"}
tags: ['Prompting', 'Pretraining Methods', 'Training Techniques', 'Fine-Tuning']
---
LLMs' sources of knowledge are data snapshots containing factual information
about entities collected at different timestamps and from different media types
(e.g. wikis, social media, etc.). Such unstructured knowledge is subject to
change due to updates through time from past to present. Equally important are
the inconsistencies and inaccuracies occurring in different information
sources. Consequently, the model's knowledge about an entity may be perturbed
while training over the sequence of snapshots or at inference time, resulting
in inconsistent and inaccurate model performance. In this work, we study the
appropriateness of Large Language Models (LLMs) as repositories of factual
knowledge. We consider twenty-four state-of-the-art LLMs that are either
closed-, partially (weights), or fully (weight and training data) open-source.
We evaluate their reliability in responding to time-sensitive factual questions
in terms of accuracy and consistency when prompts are perturbed. We further
evaluate the effectiveness of state-of-the-art methods to improve LLMs'
accuracy and consistency. We then propose "ENtity-Aware Fine-tuning" (ENAF), a
soft neurosymbolic approach aimed at providing a structured representation of
entities during fine-tuning to improve the model's performance.
