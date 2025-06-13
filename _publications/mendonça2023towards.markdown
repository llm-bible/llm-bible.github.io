---
layout: publication
title: 'Towards Multilingual Automatic Dialogue Evaluation'
authors: John Mendonça, Alon Lavie, Isabel Trancoso
conference: "Arxiv"
year: 2023
bibkey: mendonça2023towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.16795'}
tags: ['RAG', 'Applications']
---
The main limiting factor in the development of robust multilingual dialogue
evaluation metrics is the lack of multilingual data and the limited
availability of open sourced multilingual dialogue systems. In this work, we
propose a workaround for this lack of data by leveraging a strong multilingual
pretrained LLM and augmenting existing English dialogue data using Machine
Translation. We empirically show that the naive approach of finetuning a
pretrained multilingual encoder model with translated data is insufficient to
outperform the strong baseline of finetuning a multilingual model with only
source data. Instead, the best approach consists in the careful curation of
translated data using MT Quality Estimation metrics, excluding low quality
translations that hinder its performance.
