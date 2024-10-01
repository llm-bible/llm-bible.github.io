---
layout: publication
title: 'Interpreting Bias In Large Language Models: A Feature-based Approach'
authors: Prakash Nirmalendu, Roy Lee Ka Wei
conference: "Arxiv"
year: 2024
bibkey: prakash2024interpreting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12347"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'Interpretability And Explainability', 'Model Architecture']
---
Large Language Models (LLMs) such as Mistral and LLaMA have showcased remarkable performance across various natural language processing (NLP) tasks. Despite their success, these models inherit social biases from the diverse datasets on which they are trained. This paper investigates the propagation of biases within LLMs through a novel feature-based analytical approach. Drawing inspiration from causal mediation analysis, we hypothesize the evolution of bias-related features and validate them using interpretability techniques like activation and attribution patching. Our contributions are threefold: (1) We introduce and empirically validate a feature-based method for bias analysis in LLMs, applied to LLaMA-2-7B, LLaMA-3-8B, and Mistral-7B-v0.3 with templates from a professions dataset. (2) We extend our method to another form of gender bias, demonstrating its generalizability. (3) We differentiate the roles of MLPs and attention heads in bias propagation and implement targeted debiasing using a counterfactual dataset. Our findings reveal the complex nature of bias in LLMs and emphasize the necessity for tailored debiasing strategies, offering a deeper understanding of bias mechanisms and pathways for effective mitigation.
