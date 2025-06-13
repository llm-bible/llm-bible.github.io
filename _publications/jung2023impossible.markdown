---
layout: publication
title: 'Impossible Distillation: From Low-quality Model To High-quality Dataset & Model For Summarization And Paraphrasing'
authors: Jaehun Jung, Peter West, Liwei Jiang, Faeze Brahman, Ximing Lu, Jillian Fisher, Taylor Sorensen, Yejin Choi
conference: "Arxiv"
year: 2023
bibkey: jung2023impossible
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2305.16635'}
tags: ['Efficiency and Optimization', 'Distillation', 'GPT', 'Model Architecture', 'Tools', 'Applications']
---
We present Impossible Distillation, a novel framework for paraphrasing and
sentence summarization, that distills a high-quality dataset and model from a
low-quality teacher that itself cannot perform these tasks. Unlike prior works
that rely on an extreme-scale teacher model (e.g., GPT3) or task-specific
architecture, we hypothesize and verify the paraphrastic proximity intrinsic to
pre-trained LMs (e.g., GPT2), where paraphrases occupy a proximal subspace in
the LM distribution. By identifying and distilling generations from these
subspaces, Impossible Distillation produces a high-quality dataset and model
even from GPT2-scale LMs. We evaluate our method on multiple benchmarks
spanning unconstrained / syntax-controlled paraphrase generation and sentence
summarization. Our model with 770M parameters consistently outperforms strong
baselines, including models distilled from ChatGPT, and sometimes, even ChatGPT
itself. Also, we find that our distilled dataset from 1.5B LMs exhibits higher
diversity and fidelity than up to 13 times larger datasets.
