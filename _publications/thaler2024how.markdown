---
layout: publication
title: 'How Far Can Bias Go? -- Tracing Bias From Pretraining Data To Alignment'
authors: Marion Thaler, Abdullatif Köksal, Alina Leidinger, Anna Korhonen, Hinrich Schütze
conference: "Arxiv"
year: 2024
bibkey: thaler2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.19240"}
tags: ['Training Techniques', 'Ethics and Bias', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'Pre-Training', 'Applications']
---
As LLMs are increasingly integrated into user-facing applications, addressing
biases that perpetuate societal inequalities is crucial. While much work has
gone into measuring or mitigating biases in these models, fewer studies have
investigated their origins. Therefore, this study examines the correlation
between gender-occupation bias in pre-training data and their manifestation in
LLMs, focusing on the Dolma dataset and the OLMo model. Using zero-shot
prompting and token co-occurrence analyses, we explore how biases in training
data influence model outputs. Our findings reveal that biases present in
pre-training data are amplified in model outputs. The study also examines the
effects of prompt types, hyperparameters, and instruction-tuning on bias
expression, finding instruction-tuning partially alleviating representational
bias while still maintaining overall stereotypical gender associations, whereas
hyperparameters and prompting variation have a lesser effect on bias
expression. Our research traces bias throughout the LLM development pipeline
and underscores the importance of mitigating bias at the pretraining stage.
