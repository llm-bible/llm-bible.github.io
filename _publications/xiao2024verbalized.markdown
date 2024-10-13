---
layout: publication
title: 'Verbalized Machine Learning: Revisiting Machine Learning With Language Models'
authors: Xiao Tim Z., Bamler Robert, Schölkopf Bernhard, Liu Weiyang
conference: "Arxiv"
year: 2024
bibkey: xiao2024verbalized
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04344"}
tags: ['Ethics And Bias', 'Interpretability And Explainability', 'Prompting', 'Tools', 'Training Techniques']
---
Motivated by the large progress made by large language models (LLMs), we
introduce the framework of verbalized machine learning (VML). In contrast to
conventional machine learning models that are typically optimized over a
continuous parameter space, VML constrains the parameter space to be
human-interpretable natural language. Such a constraint leads to a new
perspective of function approximation, where an LLM with a text prompt can be
viewed as a function parameterized by the text prompt. Guided by this
perspective, we revisit classical machine learning problems, such as regression
and classification, and find that these problems can be solved by an
LLM-parameterized learner and optimizer. The major advantages of VML include
(1) easy encoding of inductive bias: prior knowledge about the problem and
hypothesis class can be encoded in natural language and fed into the
LLM-parameterized learner; (2) automatic model class selection: the optimizer
can automatically select a concrete model class based on data and verbalized
prior knowledge, and it can update the model class during training; and (3)
interpretable learner updates: the LLM-parameterized optimizer can provide
explanations for why each learner update is performed. We conduct several
studies to empirically evaluate the effectiveness of VML, and hope that VML can
serve as a stepping stone to stronger interpretability and trustworthiness in
ML.
