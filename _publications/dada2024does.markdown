---
layout: publication
title: 'Does Biomedical Training Lead To Better Medical Performance?'
authors: Amin Dada, Marie Bauer, Amanda Butler Contreras, Osman Alperen Koraş, Constantin Marc Seibold, Kaleb E Smith, Jens Kleesiek
conference: "Arxiv"
year: 2024
bibkey: dada2024does
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2404.04067'}
  - {name: "Code", url: 'https://github.com/TIO-IKIM/CLUE'}
tags: ['Has Code', 'Training Techniques', 'Merging', 'Fine-Tuning', 'Reinforcement Learning', 'Pretraining Methods']
---
Large Language Models (LLMs) are expected to significantly contribute to
patient care, diagnostics, and administrative processes. Emerging biomedical
LLMs aim to address healthcare-specific challenges, including privacy demands
and computational constraints. Assessing the models' suitability for this
sensitive application area is of the utmost importance. However, biomedical
training has not been systematically evaluated on medical tasks. This study
investigates the effect of biomedical training in the context of six practical
medical tasks evaluating \\(25\\) models. In contrast to previous evaluations, our
results reveal a performance decline in nine out of twelve biomedical models
after fine-tuning, particularly on tasks involving hallucinations, ICD10
coding, and instruction adherence. General-domain models like
Meta-Llama-3.1-70B-Instruct outperformed their biomedical counterparts,
indicating a trade-off between domain-specific fine-tuning and general medical
task performance. We open-source all evaluation scripts and datasets at
https://github.com/TIO-IKIM/CLUE to support further research in this critical
area.
