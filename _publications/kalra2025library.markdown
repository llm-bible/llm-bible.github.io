---
layout: publication
title: 'Verdict: A Library For Scaling Judge-time Compute'
authors: Nimit Kalra, Leonard Tang
conference: "Arxiv"
year: 2025
bibkey: kalra2025library
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.18018'}
tags: ['RAG', 'Interpretability and Explainability', 'Prompting', 'Tools']
---
The use of LLMs as automated judges ("LLM-as-a-judge") is now widespread, yet
standard judges suffer from a multitude of reliability issues. To address these
challenges, we introduce Verdict, an open-source library for scaling judge-time
compute to enhance the accuracy, reliability, and interpretability of automated
evaluators. Verdict leverages the composition of modular reasoning units --
such as verification, debate, and aggregation -- and increased inference-time
compute to improve LLM judge quality. Across a variety of challenging tasks
such as content moderation, fact-checking, and hallucination detection, Verdict
judges achieve state-of-the-art (SOTA) or near-SOTA performance, surpassing
orders-of-magnitude larger fine-tuned judges, prompted judges, and reasoning
models. Ultimately, we hope Verdict serves as a useful framework for
researchers and practitioners building scalable, interpretable, and reliable
LLM-based evaluators.
