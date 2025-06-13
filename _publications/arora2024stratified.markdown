---
layout: publication
title: 'SPAFIT: Stratified Progressive Adaptation Fine-tuning For Pre-trained Large Language Models'
authors: Samir Arora, Liangliang Wang
conference: "Arxiv"
year: 2024
bibkey: arora2024stratified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00201"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Transformer', 'Fine-Tuning']
---
Full fine-tuning is a popular approach to adapt Transformer-based pre-trained
large language models to a specific downstream task. However, the substantial
requirements for computational power and storage have discouraged its
widespread use. Moreover, increasing evidence of catastrophic forgetting and
overparameterization in the Transformer architecture has motivated researchers
to seek more efficient fine-tuning (PEFT) methods. Commonly known
parameter-efficient fine-tuning methods like LoRA and BitFit are typically
applied across all layers of the model. We propose a PEFT method, called
Stratified Progressive Adaptation Fine-tuning (SPAFIT), based on the
localization of different types of linguistic knowledge to specific layers of
the model. Our experiments, conducted on nine tasks from the GLUE benchmark,
show that our proposed SPAFIT method outperforms other PEFT methods while
fine-tuning only a fraction of the parameters adjusted by other methods.
