---
layout: publication
title: 'Superscopes: Amplifying Internal Feature Representations For Language Model Interpretation'
authors: Jonathan Jacobi, Gal Niv
conference: "Arxiv"
year: 2025
bibkey: jacobi2025amplifying
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.02078'}
tags: ['Prompting', 'Interpretability and Explainability', 'Training Techniques', 'Merging']
---
Understanding and interpreting the internal representations of large language
models (LLMs) remains an open challenge. Patchscopes introduced a method for
probing internal activations by patching them into new prompts, prompting
models to self-explain their hidden representations. We introduce Superscopes,
a technique that systematically amplifies superposed features in MLP outputs
(multilayer perceptron) and hidden states before patching them into new
contexts. Inspired by the "features as directions" perspective and the
Classifier-Free Guidance (CFG) approach from diffusion models, Superscopes
amplifies weak but meaningful features, enabling the interpretation of internal
representations that previous methods failed to explain-all without requiring
additional training. This approach provides new insights into how LLMs build
context and represent complex concepts, further advancing mechanistic
interpretability.
