---
layout: publication
title: 'Plausibility Vaccine: Injecting LLM Knowledge For Event Plausibility'
authors: Jacob Chmura, Jonah Dauvet, Sebastian Sabry
conference: "Arxiv"
year: 2025
bibkey: chmura2025plausibility
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.12667'}
  - {name: "Code", url: 'https://github.com/Jacob-Chmura/plausibility-vaccine'}
tags: ['Has Code', 'Training Techniques', 'BERT', 'Model Architecture', 'Fine-Tuning', 'Merging', 'Prompting', 'Pretraining Methods']
---
Despite advances in language modelling, distributional methods that build
semantic representations from co-occurrences fail to discriminate between
plausible and implausible events. In this work, we investigate how plausibility
prediction can be improved by injecting latent knowledge prompted from large
language models using parameter-efficient fine-tuning. We train 12 task
adapters to learn various physical properties and association measures and
perform adapter fusion to compose latent semantic knowledge from each task on
top of pre-trained AlBERT embeddings. We automate auxiliary task data
generation, which enables us to scale our approach and fine-tune our learned
representations across two plausibility datasets. Our code is available at
https://github.com/Jacob-Chmura/plausibility-vaccine.
