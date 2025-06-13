---
layout: publication
title: 'Frame Representation Hypothesis: Multi-token LLM Interpretability And Concept-guided Text Generation'
authors: Pedro H. V. Valois, Lincon S. Souza, Erica K. Shimomoto, Kazuhiro Fukui
conference: "Arxiv"
year: 2024
bibkey: valois2024frame
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.07334'}
  - {name: "Code", url: 'https://github.com/phvv-me/frame-representation-hypothesis.git'}
tags: ['Has Code', 'Language Modeling', 'Interpretability and Explainability', 'RAG', 'Applications', 'Tools', 'Ethics and Bias']
---
Interpretability is a key challenge in fostering trust for Large Language
Models (LLMs), which stems from the complexity of extracting reasoning from
model's parameters. We present the Frame Representation Hypothesis, a
theoretically robust framework grounded in the Linear Representation Hypothesis
(LRH) to interpret and control LLMs by modeling multi-token words. Prior
research explored LRH to connect LLM representations with linguistic concepts,
but was limited to single token analysis. As most words are composed of several
tokens, we extend LRH to multi-token words, thereby enabling usage on any
textual data with thousands of concepts. To this end, we propose words can be
interpreted as frames, ordered sequences of vectors that better capture
token-word relationships. Then, concepts can be represented as the average of
word frames sharing a common concept. We showcase these tools through Top-k
Concept-Guided Decoding, which can intuitively steer text generation using
concepts of choice. We verify said ideas on Llama 3.1, Gemma 2, and Phi 3
families, demonstrating gender and language biases, exposing harmful content,
but also potential to remediate them, leading to safer and more transparent
LLMs. Code is available at
https://github.com/phvv-me/frame-representation-hypothesis.git
