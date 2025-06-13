---
layout: publication
title: 'Reasoning Capabilities And Invariability Of Large Language Models'
authors: Alessandro Raganato, Rafael Peñaloza, Marco Viviani, Gabriella Pasi
conference: "Arxiv"
year: 2025
bibkey: raganato2025reasoning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.00776"}
tags: ['Few-Shot', 'Reinforcement Learning', 'Prompting', 'Applications', 'In-Context Learning']
---
Large Language Models (LLMs) have shown remarkable capabilities in
manipulating natural language across multiple applications, but their ability
to handle simple reasoning tasks is often questioned. In this work, we aim to
provide a comprehensive analysis of LLMs' reasoning competence, specifically
focusing on their prompt dependency. In particular, we introduce a new
benchmark dataset with a series of simple reasoning questions demanding shallow
logical reasoning. Aligned with cognitive psychology standards, the questions
are confined to a basic domain revolving around geometric figures, ensuring
that responses are independent of any pre-existing intuition about the world
and rely solely on deduction. An empirical analysis involving zero-shot and
few-shot prompting across 24 LLMs of different sizes reveals that, while LLMs
with over 70 billion parameters perform better in the zero-shot setting, there
is still a large room for improvement. An additional test with chain-of-thought
prompting over 22 LLMs shows that this additional prompt can aid or damage the
performance of models, depending on whether the rationale is required before or
after the answer.
