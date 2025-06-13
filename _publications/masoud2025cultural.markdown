---
layout: publication
title: 'Cultural Alignment In Large Language Models Using Soft Prompt Tuning'
authors: Reem I. Masoud, Martin Ferianc, Philip Treleaven, Miguel Rodrigues
conference: "Arxiv"
year: 2025
bibkey: masoud2025cultural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.16094"}
tags: ['Fine-Tuning', 'Agentic', 'Efficiency and Optimization', 'Tools', 'Survey Paper', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large Language Model (LLM) alignment conventionally relies on supervised
fine-tuning or reinforcement learning based alignment frameworks. These methods
typically require labeled or preference datasets and involve updating model
weights to align the LLM with the training objective or reward model.
Meanwhile, in social sciences such as cross-cultural studies, factor analysis
is widely used to uncover underlying dimensions or latent variables that
explain observed patterns in survey data. The non-differentiable nature of
these measurements deriving from survey data renders the former alignment
methods infeasible for alignment with cultural dimensions. To overcome this, we
propose a parameter efficient strategy that combines soft prompt tuning, which
freezes the model parameters while modifying the input prompt embeddings, with
Differential Evolution (DE), a black-box optimization method for cases where a
differentiable objective is unattainable. This strategy ensures alignment
consistency without the need for preference data or model parameter updates,
significantly enhancing efficiency and mitigating overfitting. Our method
demonstrates significant improvements in LLama-3-8B-Instruct's cultural
dimensions across multiple regions, outperforming both the Naive LLM and the
In-context Learning (ICL) baseline, and effectively bridges computational
models with human cultural nuances.
