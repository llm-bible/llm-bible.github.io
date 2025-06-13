---
layout: publication
title: 'Generaitor: Tree-in-the-loop Text Generation For Language Model Explainability And Adaptation'
authors: Thilo Spinner, Rebecca Kehlbeck, Rita Sevastjanova, Tobias Stähle, Daniel A. Keim, Oliver Deussen, Mennatallah El-assady
conference: "Arxiv"
year: 2024
bibkey: spinner2024tree
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.07627"}
tags: ['Fine-Tuning', 'Ethics and Bias', 'Applications', 'Interpretability and Explainability', 'Language Modeling', 'Reinforcement Learning', 'Interpretability', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) are widely deployed in various downstream tasks,
e.g., auto-completion, aided writing, or chat-based text generation. However,
the considered output candidates of the underlying search algorithm are
under-explored and under-explained. We tackle this shortcoming by proposing a
tree-in-the-loop approach, where a visual representation of the beam search
tree is the central component for analyzing, explaining, and adapting the
generated outputs. To support these tasks, we present generAItor, a visual
analytics technique, augmenting the central beam search tree with various
task-specific widgets, providing targeted visualizations and interaction
possibilities. Our approach allows interactions on multiple levels and offers
an iterative pipeline that encompasses generating, exploring, and comparing
output candidates, as well as fine-tuning the model based on adapted data. Our
case study shows that our tool generates new insights in gender bias analysis
beyond state-of-the-art template-based methods. Additionally, we demonstrate
the applicability of our approach in a qualitative user study. Finally, we
quantitatively evaluate the adaptability of the model to few samples, as
occurring in text-generation use cases.
