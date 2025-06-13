---
layout: publication
title: '60 Data Points Are Sufficient To Fine-tune Llms For Question-answering'
authors: Junjie Ye, Yuming Yang, Qi Zhang, Tao Gui, Xuanjing Huang, Peng Wang, Zhongchao Shi, Jianping Fan
conference: "Arxiv"
year: 2024
bibkey: ye2024data
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2409.15825'}
tags: ['Training Techniques', 'Fine-Tuning', 'Reinforcement Learning', 'Pre-Training', 'Pretraining Methods']
---
Large language models (LLMs) encode extensive world knowledge through
pre-training on massive datasets, which can then be fine-tuned for the
question-answering (QA) task. However, effective strategies for fine-tuning
LLMs for the QA task remain largely unexplored. To address this gap, we
categorize supervised fine-tuning (SFT) data based on the extent of knowledge
memorized by the pretrained LLMs and conduct a series of empirical analyses.
Our experiments, involving four LLMs from three different model families, focus
on three key factors: the amount of data required for SFT, the impact of
different SFT datasets on model performance, and how data requirements vary
across LLMs. The results show that as few as 60 data points during the SFT
stage can activate the knowledge encoded during pre-training, enabling LLMs to
perform the QA task. Additionally, SFT with data of varying memory levels has a
significant impact on LLM performance, with the optimal dataset differing based
on the specific model being fine-tuned. Future research will delve deeper into
the mechanisms underlying these phenomena.
