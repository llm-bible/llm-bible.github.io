---
layout: publication
title: 'Enhancing Temporal Understanding In Audio Question Answering For Large Audio Language Models'
authors: Arvind Krishna Sridhar, Yinyi Guo, Erik Visser
conference: "Arxiv"
year: 2024
bibkey: sridhar2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06223"}
tags: ['Fine-Tuning', 'Applications', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods']
---
The Audio Question Answering (AQA) task includes audio event classification,
audio captioning, and open-ended reasoning. Recently, AQA has garnered
attention due to the advent of Large Audio Language Models (LALMs). Current
literature focuses on constructing LALMs by integrating audio encoders with
text-only Large Language Models (LLMs) through a projection module. While LALMs
excel in general audio understanding, they are limited in temporal reasoning,
which may hinder their commercial applications and on-device deployment. This
paper addresses these challenges and limitations in audio temporal reasoning.
First, we introduce a data augmentation technique for generating reliable audio
temporal questions and answers using an LLM. Second, we perform a further
fine-tuning of an existing baseline using curriculum learning strategy to
specialize in temporal reasoning without compromising performance on fine-tuned
tasks. We demonstrate the performance of our model using state-of-the-art LALMs
on public audio benchmark datasets. Third, we implement our AQA model on-device
locally and investigate its CPU inference for edge applications.
