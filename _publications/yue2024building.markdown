---
layout: publication
title: 'Building A Family Of Data Augmentation Models For Low-cost LLM Fine-tuning On The Cloud'
authors: Yuanhao Yue, Chengyu Wang, Jun Huang, Peng Wang
conference: "Arxiv"
year: 2024
bibkey: yue2024building
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.04871"}
tags: ['Fine-Tuning', 'Tools', 'Efficiency and Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods']
---
Specializing LLMs in various domain-specific tasks has emerged as a critical
step towards achieving high performance. However, the construction and
annotation of datasets in specific domains are always very costly. Apart from
using superior and expensive closed-source LLM APIs to construct datasets, some
open-source models have become strong enough to handle dataset construction in
many scenarios. Thus, we present a family of data augmentation models designed
to significantly improve the efficiency for model fine-tuning. These models,
trained based on sufficiently small LLMs, support key functionalities with low
inference costs: instruction expansion, instruction refinement, and
instruction-response pair expansion. To fulfill this goal, we first construct
an automatic data collection system with seed datasets generated from both
public repositories and our in-house datasets. This system leverages powerful
LLMs to expand, refine and re-write the instructions and responses,
incorporating quality assessment techniques. Following this, we introduce the
training process of our models, which effectively distills task-solving and
text synthesis abilities from teacher LLMs. Finally, we demonstrate how we
integrate these functionalities into a machine learning platform to support
low-cost LLM fine-tuning from both dataset preparation and training
perspectives for users. Experiments and an application study prove the
effectiveness of our approach.
