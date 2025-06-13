---
layout: publication
title: 'Generating Synthetic Datasets For Few-shot Prompt Tuning'
authors: Xu Guo, Zilin Du, Boyang Li, Chunyan Miao
conference: "Arxiv"
year: 2024
bibkey: guo2024generating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.10865'}
tags: ['Few-Shot', 'RAG', 'Training Techniques', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
A major limitation of prompt tuning is its dependence on large labeled
training datasets. Under few-shot learning settings, prompt tuning lags far
behind full-model fine-tuning, limiting its scope of application. In this
paper, we leverage the powerful LLMs to synthesize task-specific labeled data
for training the soft prompts. We first introduce a distribution-aligned
weighted generator tuning (DawGen) method to encourage generating
in-distribution data that aligns with the few-shot real data. Then, we train
soft prompts on both synthetic and real datasets using a gradient surgery
approach, which eliminates the conflicting gradients from different data
sources. Experiments on seven sentence-pair classification datasets demonstrate
the effectiveness of our proposed method for boosting prompt tuning in few-shot
learning settings. Results on QQP, MRPC, and SICK datasets are even comparable
to the performance of transfer learning from large real-world datasets, showing
the promise of synthetic data as an alternative for enhancing soft prompt
tuning.
