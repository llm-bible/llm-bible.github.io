---
layout: publication
title: 'Faithfulness Of LLM Self-explanations For Commonsense Tasks: Larger Is Better, And Instruction-tuning Allows Trade-offs But Not Pareto Dominance'
authors: Noah Y. Siegel, Nicolas Heess, Maria Perez-ortiz, Oana-maria Camburu
conference: "Arxiv"
year: 2025
bibkey: siegel2025faithfulness
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.13445'}
tags: ['Prompting', 'Fine-Tuning', 'Interpretability and Explainability', 'Responsible AI']
---
As large language models (LLMs) become increasingly capable, ensuring that
their self-generated explanations are faithful to their internal
decision-making process is critical for safety and oversight. In this work, we
conduct a comprehensive counterfactual faithfulness analysis across 62 models
from 8 families, encompassing both pretrained and instruction-tuned variants
and significantly extending prior studies of counterfactual tests. We introduce
phi-CCT, a simplified variant of the Correlational Counterfactual Test, which
avoids the need for token probabilities while explaining most of the variance
of the original test. Our findings reveal clear scaling trends: larger models
are consistently more faithful on our metrics. However, when comparing
instruction-tuned and human-imitated explanations, we find that observed
differences in faithfulness can often be attributed to explanation verbosity,
leading to shifts along the true-positive/false-positive Pareto frontier. While
instruction-tuning and prompting can influence this trade-off, we find limited
evidence that they fundamentally expand the frontier of explanatory
faithfulness beyond what is achievable with pretrained models of comparable
size. Our analysis highlights the nuanced relationship between
instruction-tuning, verbosity, and the faithful representation of model
decision processes.
