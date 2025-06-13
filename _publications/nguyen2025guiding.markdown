---
layout: publication
title: 'Guiding Llms To Generate High-fidelity And High-quality Counterfactual Explanations For Text Classification'
authors: Van Bach Nguyen, Christin Seifert, Jörg Schlötterer
conference: "Arxiv"
year: 2025
bibkey: nguyen2025guiding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.04463'}
tags: ['Language Modeling', 'Interpretability and Explainability', 'Security', 'Training Techniques', 'Applications', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
The need for interpretability in deep learning has driven interest in
counterfactual explanations, which identify minimal changes to an instance that
change a model's prediction. Current counterfactual (CF) generation methods
require task-specific fine-tuning and produce low-quality text. Large Language
Models (LLMs), though effective for high-quality text generation, struggle with
label-flipping counterfactuals (i.e., counterfactuals that change the
prediction) without fine-tuning. We introduce two simple classifier-guided
approaches to support counterfactual generation by LLMs, eliminating the need
for fine-tuning while preserving the strengths of LLMs. Despite their
simplicity, our methods outperform state-of-the-art counterfactual generation
methods and are effective across different LLMs, highlighting the benefits of
guiding counterfactual generation by LLMs with classifier information. We
further show that data augmentation by our generated CFs can improve a
classifier's robustness. Our analysis reveals a critical issue in
counterfactual generation by LLMs: LLMs rely on parametric knowledge rather
than faithfully following the classifier.
