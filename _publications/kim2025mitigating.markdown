---
layout: publication
title: 'Mitigating Bias In RAG: Controlling The Embedder'
authors: Taeyoun Kim, Jacob Springer, Aditi Raghunathan, Maarten Sap
conference: "Arxiv"
year: 2025
bibkey: kim2025mitigating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.17390'}
tags: ['RAG', 'Fairness', 'Training Techniques', 'Fine-Tuning', 'Bias Mitigation', 'Ethics and Bias', 'Pretraining Methods']
---
In retrieval augmented generation (RAG) systems, each individual component --
the LLM, embedder, and corpus -- could introduce biases in the form of skews
towards outputting certain perspectives or identities. In this work, we study
the conflict between biases of each component and their relationship to the
overall bias of the RAG system, which we call bias conflict. Examining both
gender and political biases as case studies, we show that bias conflict can be
characterized through a linear relationship among components despite its
complexity in 6 different LLMs. Through comprehensive fine-tuning experiments
creating 120 differently biased embedders, we demonstrate how to control bias
while maintaining utility and reveal the importance of reverse-biasing the
embedder to mitigate bias in the overall system. Additionally, we find that
LLMs and tasks exhibit varying sensitivities to the embedder bias, a crucial
factor to consider for debiasing. Our results underscore that a fair RAG system
can be better achieved by carefully controlling the bias of the embedder rather
than increasing its fairness.
