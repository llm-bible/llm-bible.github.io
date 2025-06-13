---
layout: publication
title: 'PLDR-LLM: Large Language Model From Power Law Decoder Representations'
authors: Burc Gokden
conference: "Arxiv"
year: 2024
bibkey: gokden2024pldr
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.16703"}
tags: ['Transformer', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Pretraining Methods', 'Few-Shot']
---
We present the Large Language Model from Power Law Decoder Representations
(PLDR-LLM), a language model that leverages non-linear and linear
transformations through Power Law Graph Attention mechanism to generate
well-defined deductive and inductive outputs. We pretrain the PLDR-LLMs of
varying layer sizes with a small batch size of 32 and \\(\sim\\)8B tokens from the
RefinedWeb dataset, and show that they achieve competitive performance in
zero-shot and few-shot settings compared to scaled dot-product LLMs of similar
model size reported in the literature. We show that deductive outputs of
PLDR-LLMs can be used to compare model characteristics or improve the
performance by introducing the Directed Acyclic Graph (DAG) loss as a metric
and regularizer. Our results indicate that the initial maximum learning rate
and warm-up steps have a lasting impact on deductive outputs throughout the
pretraining. We provide a detailed description of PLDR-LLM architecture, its
implementation and the pretraining procedure.
