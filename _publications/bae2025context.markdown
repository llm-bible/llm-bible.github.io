---
layout: publication
title: 'Decap: Context-adaptive Prompt Generation For Debiasing Zero-shot Question Answering In Large Language Models'
authors: Suyoung Bae, Yunseok Choi, Jee-hyong Lee
conference: "Arxiv"
year: 2025
bibkey: bae2025context
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.19426'}
tags: ['RAG', 'Fairness', 'Applications', 'Prompting', 'Bias Mitigation', 'Ethics and Bias']
---
While Large Language Models (LLMs) excel in zero-shot Question Answering
(QA), they tend to expose biases in their internal knowledge when faced with
socially sensitive questions, leading to a degradation in performance. Existing
zero-shot methods are efficient but fail to consider context and prevent bias
propagation in the answers. To address this, we propose DeCAP, a method for
debiasing LLMs using Context-Adaptive Prompt Generation. DeCAP leverages a
Question Ambiguity Detection to take appropriate debiasing actions based on the
context and a Neutral Answer Guidance Generation to suppress the LLMs make
objective judgments about the context, minimizing the propagation of bias from
their internal knowledge. Our various experiments across eight LLMs show that
DeCAP achieves state-of-the-art zero-shot debiased QA performance. This
demonstrates DeCAP's efficacy in enhancing the fairness and accuracy of LLMs in
diverse QA settings.
