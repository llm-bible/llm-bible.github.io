---
layout: publication
title: 'Enhancing Cross-language Code Translation Via Task-specific Embedding Alignment In Retrieval-augmented Generation'
authors: Manish Bhattarai, Minh Vu, Javier E. Santos, Ismael Boureima, Daniel O' Malley
conference: "Arxiv"
year: 2024
bibkey: bhattarai2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.05159"}
tags: ['Efficiency and Optimization', 'Training Techniques', 'Tools', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
We introduce a novel method to enhance cross-language code translation from
Fortran to C++ by integrating task-specific embedding alignment into a
Retrieval-Augmented Generation (RAG) framework. Unlike conventional retrieval
approaches that utilize generic embeddings agnostic to the downstream task, our
strategy aligns the retrieval model directly with the objective of maximizing
translation quality, as quantified by the CodeBLEU metric. This alignment
ensures that the embeddings are semantically and syntactically meaningful for
the specific code translation task. Our methodology involves constructing a
dataset of 25,000 Fortran code snippets sourced from Stack-V2 dataset and
generating their corresponding C++ translations using the LLaMA 3.1-8B language
model. We compute pairwise CodeBLEU scores between the generated translations
and ground truth examples to capture fine-grained similarities. These scores
serve as supervision signals in a contrastive learning framework, where we
optimize the embedding model to retrieve Fortran-C++ pairs that are most
beneficial for improving the language model's translation performance. By
integrating these CodeBLEU-optimized embeddings into the RAG framework, our
approach significantly enhances both retrieval accuracy and code generation
quality over methods employing generic embeddings. On the HPC Fortran2C++
dataset, our method elevates the average CodeBLEU score from 0.64 to 0.73,
achieving a 14% relative improvement. On the Numerical Recipes dataset, we
observe an increase from 0.52 to 0.60, marking a 15% relative improvement.
Importantly, these gains are realized without any fine-tuning of the language
model, underscoring the efficiency and practicality of our approach.
