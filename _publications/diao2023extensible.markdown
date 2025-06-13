---
layout: publication
title: 'Lmflow: An Extensible Toolkit For Finetuning And Inference Of Large Foundation Models'
authors: Shizhe Diao, Rui Pan, Hanze Dong, Ka Shun Shum, Jipeng Zhang, Wei Xiong, Tong Zhang
conference: "Arxiv"
year: 2023
bibkey: diao2023extensible
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2306.12420'}
  - {name: "Code", url: 'https://github.com/OptimalScale/LMFlow'}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Applications', 'Tools', 'Fine-Tuning', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Foundation models have demonstrated a great ability to achieve general
human-level intelligence far beyond traditional approaches. As the technique
keeps attracting attention from the AI community, an increasing number of
foundation models are becoming publicly accessible. However, a significant
shortcoming of most of these models lies in their performance in
specialized-domain and task-specific applications, necessitating domain- and
task-aware fine-tuning to develop effective scientific language models. As the
number of available foundation models and specialized tasks keeps growing, the
job of training scientific language models becomes highly nontrivial. In this
paper, we initiate steps to tackle this issue. We introduce an extensible and
lightweight toolkit, LMFlow, which aims to simplify the domain- and task-aware
finetuning of general foundation models. LMFlow offers a complete finetuning
workflow for a foundation model to support specialized training with limited
computing resources. Furthermore, it supports continuous pretraining,
instruction tuning, parameter-efficient finetuning, alignment tuning, inference
acceleration, long context generalization, model customization, and even
multimodal finetuning, along with carefully designed and extensible APIs. This
toolkit has been thoroughly tested and is available at
https://github.com/OptimalScale/LMFlow.
