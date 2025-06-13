---
layout: publication
title: 'Outlier Dimensions Encode Task-specific Knowledge'
authors: William Rudman, Catherine Chen, Carsten Eickhoff
conference: "Arxiv"
year: 2023
bibkey: rudman2023outlier
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2310.17715'}
tags: ['Pre-Training', 'Fine-Tuning', 'Training Techniques', 'Pretraining Methods']
---
Representations from large language models (LLMs) are known to be dominated
by a small subset of dimensions with exceedingly high variance. Previous works
have argued that although ablating these outlier dimensions in LLM
representations hurts downstream performance, outlier dimensions are
detrimental to the representational quality of embeddings. In this study, we
investigate how fine-tuning impacts outlier dimensions and show that 1) outlier
dimensions that occur in pre-training persist in fine-tuned models and 2) a
single outlier dimension can complete downstream tasks with a minimal error
rate. Our results suggest that outlier dimensions can encode crucial
task-specific knowledge and that the value of a representation in a single
outlier dimension drives downstream model decisions.
