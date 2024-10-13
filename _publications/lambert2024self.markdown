---
layout: publication
title: 'Self-directed Synthetic Dialogues And Revisions Technical Report'
authors: Lambert Nathan, Schoelkopf Hailey, Gokaslan Aaron, Soldaini Luca, Pyatkin Valentina, Castricato Louis
conference: "Arxiv"
year: 2024
bibkey: lambert2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.18421"}
tags: ['Fine Tuning', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Synthetic data has become an important tool in the fine-tuning of language
models to follow instructions and solve complex problems. Nevertheless, the
majority of open data to date is often lacking multi-turn data and collected on
closed models, limiting progress on advancing open fine-tuning methods. We
introduce Self Directed Synthetic Dialogues (SDSD), an experimental dataset
consisting of guided conversations of language models talking to themselves.
The dataset consists of multi-turn conversations generated with DBRX, Llama 2
70B, and Mistral Large, all instructed to follow a conversation plan generated
prior to the conversation. We also explore including principles from
Constitutional AI and other related works to create synthetic preference data
via revisions to the final conversation turn. We hope this work encourages
further exploration in multi-turn data and the use of open models for expanding
the impact of synthetic data.
