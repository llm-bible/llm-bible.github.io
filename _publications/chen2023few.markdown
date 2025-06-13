---
layout: publication
title: 'Few-shot Data Synthesis For Open Domain Multi-hop Question Answering'
authors: Mingda Chen, Xilun Chen, Wen-tau Yih
conference: "Arxiv"
year: 2023
bibkey: chen2023few
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13691"}
tags: ['Tools', 'GPT', 'Applications', 'Model Architecture', 'Few-Shot', 'Prompting']
---
Few-shot learning for open domain multi-hop question answering typically
relies on the incontext learning capability of large language models (LLMs).
While powerful, these LLMs usually contain tens or hundreds of billions of
parameters, making them rather inefficient at inference time. To improve
performance of smaller language models, we propose a data synthesis framework
for multi-hop question answering that requires less than 10 human annotated
question answer pairs. Our framework depends only on rich, naturally-occurring
relationships among documents and is built upon the data generation functions
parameterized by LLMs and prompts. We synthesize millions of multi-hop
questions and claims to finetune language models, evaluated on popular
benchmarks for multi-hop question answering and fact verification. Empirically,
our approach improves model performance significantly, allowing the finetuned
models to be competitive with GPT-3.5 based approaches while being almost
one-third the size in parameter count.
