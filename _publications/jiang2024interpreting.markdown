---
layout: publication
title: 'Interpreting Language Reward Models Via Contrastive Explanations'
authors: Junqi Jiang, Tom Bewley, Saumitra Mishra, Freddy Lecue, Manuela Veloso
conference: "Arxiv"
year: 2024
bibkey: jiang2024interpreting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.16502"}
tags: ['Prompting', 'Interpretability and Explainability', 'Tools', 'Reinforcement Learning']
---
Reward models (RMs) are a crucial component in the alignment of large
language models' (LLMs) outputs with human values. RMs approximate human
preferences over possible LLM responses to the same prompt by predicting and
comparing reward scores. However, as they are typically modified versions of
LLMs with scalar output heads, RMs are large black boxes whose predictions are
not explainable. More transparent RMs would enable improved trust in the
alignment of LLMs. In this work, we propose to use contrastive explanations to
explain any binary response comparison made by an RM. Specifically, we generate
a diverse set of new comparisons similar to the original one to characterise
the RM's local behaviour. The perturbed responses forming the new comparisons
are generated to explicitly modify manually specified high-level evaluation
attributes, on which analyses of RM behaviour are grounded. In quantitative
experiments, we validate the effectiveness of our method for finding
high-quality contrastive explanations. We then showcase the qualitative
usefulness of our method for investigating global sensitivity of RMs to each
evaluation attribute, and demonstrate how representative examples can be
automatically extracted to explain and compare behaviours of different RMs. We
see our method as a flexible framework for RM explanation, providing a basis
for more interpretable and trustworthy LLM alignment.
