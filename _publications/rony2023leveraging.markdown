---
layout: publication
title: 'Carexpert: Leveraging Large Language Models For In-car Conversational Question Answering'
authors: Md Rashad Al Hasan Rony, Christian Suess, Sinchana Ramakanth Bhat, Viju Sudhi, Julia Schneider, Maximilian Vogel, Roman Teucher, Ken E. Friedl, Soumya Sahoo
conference: "Arxiv"
year: 2023
bibkey: rony2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09536"}
tags: ['Training Techniques', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Applications']
---
Large language models (LLMs) have demonstrated remarkable performance by
following natural language instructions without fine-tuning them on
domain-specific tasks and data. However, leveraging LLMs for domain-specific
question answering suffers from severe limitations. The generated answer tends
to hallucinate due to the training data collection time (when using
off-the-shelf), complex user utterance and wrong retrieval (in
retrieval-augmented generation). Furthermore, due to the lack of awareness
about the domain and expected output, such LLMs may generate unexpected and
unsafe answers that are not tailored to the target domain. In this paper, we
propose CarExpert, an in-car retrieval-augmented conversational
question-answering system leveraging LLMs for different tasks. Specifically,
CarExpert employs LLMs to control the input, provide domain-specific documents
to the extractive and generative answering components, and controls the output
to ensure safe and domain-specific answers. A comprehensive empirical
evaluation exhibits that CarExpert outperforms state-of-the-art LLMs in
generating natural, safe and car-specific answers.
