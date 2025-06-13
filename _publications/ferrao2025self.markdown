---
layout: publication
title: 'Self-ablating Transformers: More Interpretability, Less Sparsity'
authors: Jeremias Ferrao, Luhan Mikaelson, Keenan Pepper, Natalia Perez-campanero Antolin
conference: "Arxiv"
year: 2025
bibkey: ferrao2025self
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.00509'}
  - {name: "Code", url: 'https://github.com/keenanpepper/self-ablating-transformers'}
tags: ['Attention Mechanism', 'Has Code', 'Interpretability and Explainability', 'Transformer', 'Training Techniques', 'Model Architecture', 'Pretraining Methods']
---
A growing intuition in machine learning suggests a link between sparsity and
interpretability. We introduce a novel self-ablation mechanism to investigate
this connection ante-hoc in the context of language transformers. Our approach
dynamically enforces a k-winner-takes-all constraint, forcing the model to
demonstrate selective activation across neuron and attention units. Unlike
post-hoc methods that analyze already-trained models, our approach integrates
interpretability directly into model training, promoting feature localization
from inception. Training small models on the TinyStories dataset and employing
interpretability tests, we find that self-ablation leads to more localized
circuits, concentrated feature representations, and increased neuron
specialization without compromising language modelling performance.
Surprisingly, our method also decreased overall sparsity, indicating that
self-ablation promotes specialization rather than widespread inactivity. This
reveals a complex interplay between sparsity and interpretability, where
decreased global sparsity can coexist with increased local specialization,
leading to enhanced interpretability. To facilitate reproducibility, we make
our code available at
https://github.com/keenanpepper/self-ablating-transformers.
