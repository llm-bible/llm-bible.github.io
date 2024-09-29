---
layout: publication
title: Naturalness of Attention Revisiting Attention in Code Language Models
authors: Saad Mootez, Sharma Tushar
conference: "Arxiv"
year: 2023
bibkey: saad2023naturalness
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.13508"}
tags: ['Attention Mechanism', 'BERT', 'Interpretability And Explainability', 'Model Architecture', 'Pretraining Methods', 'Transformer']
---
Language models for code such as CodeBERT offer the capability to learn advanced source code representation but their opacity poses barriers to understanding of captured properties. Recent attention analysis studies provide initial interpretability insights by focusing solely on attention weights rather than considering the wider context modeling of Transformers. This study aims to shed some light on the previously ignored factors of the attention mechanism beyond the attention weights. We conduct an initial empirical study analyzing both attention distributions and transformed representations in CodeBERT. Across two programming languages Java and Python we find that the scaled transformation norms of the input better capture syntactic structure compared to attention weights alone. Our analysis reveals characterization of how CodeBERT embeds syntactic code properties. The findings demonstrate the importance of incorporating factors beyond just attention weights for rigorously understanding neural code models. This lays the groundwork for developing more interpretable models and effective uses of attention mechanisms in program analysis.
