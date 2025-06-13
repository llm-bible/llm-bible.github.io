---
layout: publication
title: 'Training Zero-shot Generalizable End-to-end Task-oriented Dialog System Without Turn-level Dialog Annotations'
authors: Adib Mosharrof, A. B. Siddique
conference: "Arxiv"
year: 2024
bibkey: mosharrof2024training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.15055"}
tags: ['Fine-Tuning', 'GPT', 'Applications', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods']
---
Task-oriented dialogue (TOD) systems enable users to achieve their goals
through natural language interactions. Traditionally, these systems have relied
on turn-level manually annotated metadata, such as dialogue states and policy
annotations, which are expensive, time-consuming, and often inconsistent or
error-prone. This dependence limits the potential to leverage vast amounts of
readily available conversational data for training TOD systems. Additionally, a
critical challenge in TOD system design is determining when and how to access
and integrate information from external sources. Current approaches typically
expect this information to be provided alongside the dialogue context, rather
than learning to identify and retrieve it autonomously. While pre-trained large
language models (LLMs) have been used to develop TOD systems, their potential
to train such systems without laborious annotations remains largely unexplored.
This work employs multi-task instruction fine-tuning to create more efficient
and scalable TOD systems that can effectively leverage natural language
conversational data without manual annotations, while autonomously managing
external information retrieval. Our extensive experimental evaluations, using
three diverse TOD datasets and three LLMs of varying sizes, demonstrate that
our approach can generalize to new, unseen domains. Notably, our approach
outperforms both state-of-the-art models trained on annotated data and
billion-scale parameter off-the-shelf ChatGPT models.
