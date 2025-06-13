---
layout: publication
title: 'Beyond The Black Box: A Statistical Model For LLM Reasoning And Inference'
authors: Siddhartha Dalal, Vishal Misra
conference: "Arxiv"
year: 2024
bibkey: dalal2024beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.03175"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'Language Modeling', 'Interpretability and Explainability', 'Prompting', 'Applications', 'In-Context Learning']
---
This paper introduces a novel Bayesian learning model to explain the behavior
of Large Language Models (LLMs), focusing on their core optimization metric of
next token prediction. We develop a theoretical framework based on an ideal
generative text model represented by a multinomial transition probability
matrix with a prior, and examine how LLMs approximate this matrix. Key
contributions include: (i) a continuity theorem relating embeddings to
multinomial distributions, (ii) a demonstration that LLM text generation aligns
with Bayesian learning principles, (iii) an explanation for the emergence of
in-context learning in larger models, (iv) empirical validation using
visualizations of next token probabilities from an instrumented Llama model Our
findings provide new insights into LLM functioning, offering a statistical
foundation for understanding their capabilities and limitations. This framework
has implications for LLM design, training, and application, potentially guiding
future developments in the field.
