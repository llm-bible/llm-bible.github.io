---
layout: publication
title: 'Understanding And Mitigating Gender Bias In Llms Via Interpretable Neuron Editing'
authors: Zeping Yu, Sophia Ananiadou
conference: "Arxiv"
year: 2025
bibkey: yu2025understanding
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2501.14457'}
tags: ['Ethics and Bias', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Large language models (LLMs) often exhibit gender bias, posing challenges for
their safe deployment. Existing methods to mitigate bias lack a comprehensive
understanding of its mechanisms or compromise the model's core capabilities. To
address these issues, we propose the CommonWords dataset, to systematically
evaluate gender bias in LLMs. Our analysis reveals pervasive bias across models
and identifies specific neuron circuits, including gender neurons and general
neurons, responsible for this behavior. Notably, editing even a small number of
general neurons can disrupt the model's overall capabilities due to
hierarchical neuron interactions. Based on these insights, we propose an
interpretable neuron editing method that combines logit-based and causal-based
strategies to selectively target biased neurons. Experiments on five LLMs
demonstrate that our method effectively reduces gender bias while preserving
the model's original capabilities, outperforming existing fine-tuning and
editing approaches. Our findings contribute a novel dataset, a detailed
analysis of bias mechanisms, and a practical solution for mitigating gender
bias in LLMs.
