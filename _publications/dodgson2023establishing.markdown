---
layout: publication
title: 'Establishing Performance Baselines In Fine-tuning, Retrieval-augmented Generation And Soft-prompting For Non-specialist LLM Users'
authors: Jennifer Dodgson, Lin Nanzheng, Julian Peh, Akira Rafhael Janson Pattirane, Alfath Daryl Alhajir, Eko Ridho Dinarto, Joseph Lim, Syed Danyal Ahmad
conference: "Arxiv"
year: 2023
bibkey: dodgson2023establishing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.05903"}
tags: ['Fine-Tuning', 'Tools', 'GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Pretraining Methods', 'Prompting']
---
Research into methods for improving the performance of large language models
(LLMs) through fine-tuning, retrieval-augmented generation (RAG) and
soft-prompting has tended to focus on the use of highly technical or high-cost
techniques, making many of the newly discovered approaches comparatively
inaccessible to non-technical users. In this paper we tested an unmodified
version of GPT 3.5, a fine-tuned version, and the same unmodified model when
given access to a vectorised RAG database, both in isolation and in combination
with a basic, non-algorithmic soft prompt. In each case we tested the model's
ability to answer a set of 100 questions relating primarily to events that
occurred after September 2021 (the point at which GPT 3.5's training data set
ends). We found that if commercial platforms are used and default settings are
applied with no iteration in order to establish a baseline set of outputs, a
fine-tuned model outperforms GPT 3.5 Turbo, while the RAG approach
out-performed both. The application of a soft prompt significantly improved the
performance of each approach.
