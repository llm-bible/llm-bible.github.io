---
layout: publication
title: 'Dynamic Clue Bottlenecks: Towards Interpretable-by-design Visual Question Answering'
authors: Xingyu Fu, Ben Zhou, Sihao Chen, Mark Yatskar, Dan Roth
conference: "Arxiv"
year: 2023
bibkey: fu2023dynamic
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.14882'}
tags: ['Interpretability and Explainability', 'Multimodal Models', 'Applications']
---
Recent advances in multimodal large language models (LLMs) have shown extreme
effectiveness in visual question answering (VQA). However, the design nature of
these end-to-end models prevents them from being interpretable to humans,
undermining trust and applicability in critical domains. While post-hoc
rationales offer certain insight into understanding model behavior, these
explanations are not guaranteed to be faithful to the model. In this paper, we
address these shortcomings by introducing an interpretable by design model that
factors model decisions into intermediate human-legible explanations, and
allows people to easily understand why a model fails or succeeds. We propose
the Dynamic Clue Bottleneck Model ( (DCLUB), a method that is designed towards
an inherently interpretable VQA system. DCLUB provides an explainable
intermediate space before the VQA decision and is faithful from the beginning,
while maintaining comparable performance to black-box systems. Given a
question, DCLUB first returns a set of visual clues: natural language
statements of visually salient evidence from the image, and then generates the
output based solely on the visual clues. To supervise and evaluate the
generation of VQA explanations within DCLUB, we collect a dataset of 1.7k
reasoning-focused questions with visual clues. Evaluations show that our
inherently interpretable system can improve 4.64% over a comparable black-box
system in reasoning-focused questions while preserving 99.43% of performance on
VQA-v2.
