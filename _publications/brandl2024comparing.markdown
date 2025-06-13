---
layout: publication
title: 'Comparing Zero-shot Self-explanations With Human Rationales In Text Classification'
authors: Stephanie Brandl, Oliver Eberle
conference: "Arxiv"
year: 2024
bibkey: brandl2024comparing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.03296'}
tags: ['Interpretability and Explainability']
---
Instruction-tuned LLMs are able to provide an explanation about their output
to users by generating self-explanations. These do not require gradient
computations or the application of possibly complex XAI methods. In this paper,
we analyse whether this ability results in a good explanation. We evaluate
self-explanations in the form of input rationales with respect to their
plausibility to humans as well as their faithfulness to models. We study two
text classification tasks: sentiment classification and forced labour
detection, i.e., identifying pre-defined risk indicators of forced labour. In
addition to English, we include Danish and Italian translations of the
sentiment classification task and compare self-explanations to human
annotations for all samples. To allow for direct comparisons, we also compute
post-hoc feature attribution, i.e., layer-wise relevance propagation (LRP) and
analyse 4 LLMs. We show that self-explanations align more closely with human
annotations compared to LRP, while maintaining a comparable level of
faithfulness. This finding suggests that self-explanations indeed provide good
explanations for text classification.
