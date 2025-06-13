---
layout: publication
title: 'Improving Sequential Recommendations With Llms'
authors: Artun Boz, Wouter Zorgdrager, Zoe Kotti, Jesse Harte, Panos Louridas, Dietmar Jannach, Vassilios Karakoidas, Marios Fragkoulis
conference: "Arxiv"
year: 2024
bibkey: boz2024improving
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2402.01339'}
tags: ['Attention Mechanism', 'RAG', 'Training Techniques', 'Applications', 'Model Architecture', 'Fine-Tuning', 'BERT', 'GPT', 'Pretraining Methods']
---
The sequential recommendation problem has attracted considerable research
attention in the past few years, leading to the rise of numerous recommendation
models. In this work, we explore how Large Language Models (LLMs), which are
nowadays introducing disruptive effects in many AI-based applications, can be
used to build or improve sequential recommendation approaches. Specifically, we
design three orthogonal approaches and hybrids of those to leverage the power
of LLMs in different ways. In addition, we investigate the potential of each
approach by focusing on its comprising technical aspects and determining an
array of alternative choices for each one. We conduct extensive experiments on
three datasets and explore a large variety of configurations, including
different language models and baseline recommendation models, to obtain a
comprehensive picture of the performance of each approach. Among other
observations, we highlight that initializing state-of-the-art sequential
recommendation models such as BERT4Rec or SASRec with embeddings obtained from
an LLM can lead to substantial performance gains in terms of accuracy.
Furthermore, we find that fine-tuning an LLM for recommendation tasks enables
it to learn not only the tasks, but also concepts of a domain to some extent.
We also show that fine-tuning OpenAI GPT leads to considerably better
performance than fine-tuning Google PaLM 2. Overall, our extensive experiments
indicate a huge potential value of leveraging LLMs in future recommendation
approaches. We publicly share the code and data of our experiments to ensure
reproducibility.
