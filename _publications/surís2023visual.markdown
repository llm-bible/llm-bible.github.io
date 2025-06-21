---
layout: publication
title: 'Vipergpt: Visual Inference Via Python Execution For Reasoning'
authors: "D\xEDdac Sur\xEDs, Sachit Menon, Carl Vondrick"
conference: Arxiv
year: 2023
citations: 91
bibkey: "sur\xEDs2023visual"
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.08128'}]
tags: [GPT, RAG, Tools, Interpretability and Explainability]
---
Answering visual queries is a complex task that requires both visual
processing and reasoning. End-to-end models, the dominant approach for this
task, do not explicitly differentiate between the two, limiting
interpretability and generalization. Learning modular programs presents a
promising alternative, but has proven challenging due to the difficulty of
learning both the programs and modules simultaneously. We introduce ViperGPT, a
framework that leverages code-generation models to compose vision-and-language
models into subroutines to produce a result for any query. ViperGPT utilizes a
provided API to access the available modules, and composes them by generating
Python code that is later executed. This simple approach requires no further
training, and achieves state-of-the-art results across various complex visual
tasks.