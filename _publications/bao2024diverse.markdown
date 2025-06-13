---
layout: publication
title: 'Faithbench: A Diverse Hallucination Benchmark For Summarization By Modern Llms'
authors: Forrest Sheng Bao, Miaoran Li, Renyi Qu, Ge Luo, Erana Wan, Yujia Tang, Weisi Fan, Manveer Singh Tamber, Suleman Kazi, Vivek Sourabh, Mike Qi, Ruixuan Tu, Chenyu Xu, Matthew Gonzales, Ofer Mendelevitch, Amin Ahmad
conference: "Arxiv"
year: 2024
bibkey: bao2024diverse
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.13210'}
  - {name: "Code", url: 'https://github.com/vectara/FaithBench'}
tags: ['Has Code', 'RAG', 'GPT', 'Applications', 'Model Architecture']
---
Summarization is one of the most common tasks performed by large language
models (LLMs), especially in applications like Retrieval-Augmented Generation
(RAG). However, existing evaluations of hallucinations in LLM-generated
summaries, and evaluations of hallucination detection models both suffer from a
lack of diversity and recency in the LLM and LLM families considered. This
paper introduces FaithBench, a summarization hallucination benchmark comprising
challenging hallucinations made by 10 modern LLMs from 8 different families,
with ground truth annotations by human experts. ``Challenging'' here means
summaries on which popular, state-of-the-art hallucination detection models,
including GPT-4o-as-a-judge, disagreed on. Our results show GPT-4o and
GPT-3.5-Turbo produce the least hallucinations. However, even the best
hallucination detection models have near 50% accuracies on FaithBench,
indicating lots of room for future improvement. The repo is
https://github.com/vectara/FaithBench
