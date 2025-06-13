---
layout: publication
title: 'SCAR: Sparse Conditioned Autoencoders For Concept Detection And Steering In Llms'
authors: Ruben Härle, Felix Friedrich, Manuel Brack, Björn Deiseroth, Patrick Schramowski, Kristian Kersting
conference: "Arxiv"
year: 2024
bibkey: härle2024sparse
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.07122'}
tags: ['Language Modeling', 'Applications', 'Tools', 'Reinforcement Learning', 'Responsible AI']
---
Large Language Models (LLMs) have demonstrated remarkable capabilities in
generating human-like text, but their output may not be aligned with the user
or even produce harmful content. This paper presents a novel approach to detect
and steer concepts such as toxicity before generation. We introduce the Sparse
Conditioned Autoencoder (SCAR), a single trained module that extends the
otherwise untouched LLM. SCAR ensures full steerability, towards and away from
concepts (e.g., toxic content), without compromising the quality of the model's
text generation on standard evaluation benchmarks. We demonstrate the effective
application of our approach through a variety of concepts, including toxicity,
safety, and writing style alignment. As such, this work establishes a robust
framework for controlling LLM generations, ensuring their ethical and safe
deployment in real-world applications.
