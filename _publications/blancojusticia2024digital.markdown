---
layout: publication
title: 'Digital Forgetting In Large Language Models: A Survey Of Unlearning Methods'
authors: Alberto Blanco-justicia, Najeeb Jebreel, Benet Manzanares, David Sánchez, Josep Domingo-ferrer, Guillem Collell, Kuan Eeik Tan
conference: "Artificial Intelligence Review vol. 58 art. no. 90 2025"
year: 2024
bibkey: blancojusticia2024digital
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02062"}
tags: ['Training Techniques', 'Survey Paper', 'Ethics and Bias']
---
The objective of digital forgetting is, given a model with undesirable
knowledge or behavior, obtain a new model where the detected issues are no
longer present. The motivations for forgetting include privacy protection,
copyright protection, elimination of biases and discrimination, and prevention
of harmful content generation. Effective digital forgetting has to be effective
(meaning how well the new model has forgotten the undesired
knowledge/behavior), retain the performance of the original model on the
desirable tasks, and be scalable (in particular forgetting has to be more
efficient than retraining from scratch on just the tasks/data to be retained).
This survey focuses on forgetting in large language models (LLMs). We first
provide background on LLMs, including their components, the types of LLMs, and
their usual training pipeline. Second, we describe the motivations, types, and
desired properties of digital forgetting. Third, we introduce the approaches to
digital forgetting in LLMs, among which unlearning methodologies stand out as
the state of the art. Fourth, we provide a detailed taxonomy of machine
unlearning methods for LLMs, and we survey and compare current approaches.
Fifth, we detail datasets, models and metrics used for the evaluation of
forgetting, retaining and runtime. Sixth, we discuss challenges in the area.
Finally, we provide some concluding remarks.
