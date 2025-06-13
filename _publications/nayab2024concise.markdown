---
layout: publication
title: 'Concise Thoughts: Impact Of Output Length On LLM Reasoning And Cost'
authors: Sania Nayab, Giulio Rossolini, Marco Simoni, Andrea Saracino, Giorgio Buttazzo, Nicolamaria Manes, Fabrizio Giacomelli
conference: "Arxiv"
year: 2024
bibkey: nayab2024concise
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.19825'}
tags: ['Attention Mechanism', 'Interpretability and Explainability', 'RAG', 'Model Architecture', 'Prompting']
---
Today's large language models (LLMs) can solve challenging question-answering
tasks, and prompt engineering techniques, such as chain-of-thought (CoT), have
gained attention for enhancing the explanation and correctness of outputs.
However, many models and techniques tend to produce excessively verbose and
lengthy answers, leading to issues with both conciseness and generation time.
To address this, this paper analyzes the impact of output lengths on LLM
inference pipelines by introducing and proposing novel metrics to evaluate the
\textit\{correct conciseness\} of a model and related prompting techniques. Then,
we examine the impact of controlling output length through a refined prompt
engineering strategy, Constrained-CoT (CCoT), which encourages the model to
produce more concise outputs. To better understand the effects of such a
prompt, we also introduce two additional scores for analyzing the conciseness,
measured in terms of redundancy and information flow in generated answers.
Experiments on pretrained LLMs and multiple datasets demonstrate the benefits
of the proposed metrics and the effectiveness of CCoT across different models.
