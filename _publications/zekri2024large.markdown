---
layout: publication
title: 'Large Language Models As Markov Chains'
authors: Oussama Zekri, Ambroise Odonnat, Abdelhakim Benechehab, Linus Bleistein, Nicolas Boullé, Ievgen Redko
conference: "Arxiv"
year: 2024
bibkey: zekri2024large
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.02724"}
tags: ['Transformer', 'Pre-Training', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) are remarkably efficient across a wide range of
natural language processing tasks and well beyond them. However, a
comprehensive theoretical analysis of the LLMs' generalization capabilities
remains elusive. In our paper, we approach this task by drawing an equivalence
between autoregressive transformer-based language models and Markov chains
defined on a finite state space. This allows us to study the multi-step
inference mechanism of LLMs from first principles. We relate the obtained
results to the pathological behavior observed with LLMs such as repetitions and
incoherent replies with high temperature. Finally, we leverage the proposed
formalization to derive pre-training and in-context learning generalization
bounds for LLMs under realistic data and model assumptions. Experiments with
the most recent Llama and Gemma herds of models show that our theory correctly
captures their behavior in practice.
