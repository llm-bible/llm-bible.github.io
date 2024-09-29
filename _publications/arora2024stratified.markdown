---
layout: publication
title: SPAFIT Stratified Progressive Adaptation Fine45;tuning For Pre45;trained Large Language Models
authors: Arora Samir, Wang Liangliang
conference: "Arxiv"
year: 2024
bibkey: arora2024stratified
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.00201"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Transformer']
---
Full fine45;tuning is a popular approach to adapt Transformer45;based pre45;trained large language models to a specific downstream task. However the substantial requirements for computational power and storage have discouraged its widespread use. Moreover increasing evidence of catastrophic forgetting and overparameterization in the Transformer architecture has motivated researchers to seek more efficient fine45;tuning (PEFT) methods. Commonly known parameter45;efficient fine45;tuning methods like LoRA and BitFit are typically applied across all layers of the model. We propose a PEFT method called Stratified Progressive Adaptation Fine45;tuning (SPAFIT) based on the localization of different types of linguistic knowledge to specific layers of the model. Our experiments conducted on nine tasks from the GLUE benchmark show that our proposed SPAFIT method outperforms other PEFT methods while fine45;tuning only a fraction of the parameters adjusted by other methods.
