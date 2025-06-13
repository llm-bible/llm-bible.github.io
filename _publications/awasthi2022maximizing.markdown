---
layout: publication
title: 'Maximizing Use-case Specificity Through Precision Model Tuning'
authors: Pranjali Awasthi, David Recio-mitter, Yosuke Kyle Sugi
conference: "Arxiv"
year: 2022
bibkey: awasthi2022maximizing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.14206"}
tags: ['Training Techniques', 'Model Architecture', 'RAG', 'GPT', 'Pretraining Methods', 'Fine-Tuning', 'Transformer', 'Interpretability and Explainability', 'Prompting', 'Applications']
---
Language models have become increasingly popular in recent years for tasks
like information retrieval. As use-cases become oriented toward specific
domains, fine-tuning becomes default for standard performance. To fine-tune
these models for specific tasks and datasets, it is necessary to carefully tune
the model's hyperparameters and training techniques. In this paper, we present
an in-depth analysis of the performance of four transformer-based language
models on the task of biomedical information retrieval. The models we consider
are DeepMind's RETRO (7B parameters), GPT-J (6B parameters), GPT-3 (175B
parameters), and BLOOM (176B parameters). We compare their performance on the
basis of relevance, accuracy, and interpretability, using a large corpus of
480000 research papers on protein structure/function prediction as our dataset.
Our findings suggest that smaller models, with <10B parameters and fine-tuned
on domain-specific datasets, tend to outperform larger language models on
highly specific questions in terms of accuracy, relevancy, and interpretability
by a significant margin (+50% on average). However, larger models do provide
generally better results on broader prompts.
