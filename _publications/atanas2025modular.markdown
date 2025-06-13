---
layout: publication
title: 'A Modular Dataset To Demonstrate LLM Abstraction Capability'
authors: Adam Atanas, Kai Liu
conference: "Arxiv"
year: 2025
bibkey: atanas2025modular
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.17645"}
tags: ['Pretraining Methods', 'Model Architecture', 'Transformer', 'Interpretability and Explainability']
---
Large language models (LLMs) exhibit impressive capabilities but struggle
with reasoning errors due to hallucinations and flawed logic. To investigate
their internal representations of reasoning, we introduce ArrangementPuzzle, a
novel puzzle dataset with structured solutions and automated stepwise
correctness verification. We trained a classifier model on LLM activations on
this dataset and found that it achieved over 80% accuracy in predicting
reasoning correctness, implying that LLMs internally distinguish between
correct and incorrect reasoning steps, with the strongest representations in
middle-late Transformer layers. Further analysis reveals that LLMs encode
abstract reasoning concepts within the middle activation layers of the
transformer architecture, distinguishing logical from semantic equivalence.
These findings provide insights into LLM reasoning mechanisms and contribute to
improving AI reliability and interpretability, thereby offering the possibility
to manipulate and refine LLM reasoning.
